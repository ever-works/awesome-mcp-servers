# Overview

A Model Context Protocol (MCP) server implementation that provides database interaction and business intelligence capabilities through SQLite. This server enables running SQL queries, analyzing business data, and automatically generating business insight memos.

## Resources

The server exposes a single dynamic resource:

- `memo://insights`: A continuously updated business insights memo that aggregates discovered insights during analysis

## Prompts

The server provides a demonstration prompt:

- `mcp-demo`: Interactive prompt that guides users through database operations
  - Required argument: `topic` - The business domain to analyze
  - Generates appropriate database schemas and sample data
  - Guides users through analysis and insight generation
  - Integrates with the business insights memo

## Tools

The server offers six core tools organized into three categories:

### Query Tools

- `read_query`: Execute SELECT queries to read data from the database
  - Input: `query` (string): The SELECT SQL query to execute
  - Returns: Query results as array of objects

- `write_query`: Execute INSERT, UPDATE, or DELETE queries
  - Input: `query` (string): The SQL modification query
  - Returns: `{ affected_rows: number }`

- `create_table`: Create new tables in the database
  - Input: `query` (string): CREATE TABLE SQL statement
  - Returns: Confirmation of table creation

### Schema Tools

- `list_tables`: Get a list of all tables in the database
  - No input required
  - Returns: Array of table names

- `describe_table`: View schema information for a specific table
  - Input: `table_name` (string): Name of table to describe
  - Returns: Array of column definitions with names and types

### Analysis Tools

- `append_insight`: Add new business insights to the memo resource
  - Input: `insight` (string): Business insight discovered from data analysis
  - Returns: Confirmation of insight addition
  - Triggers update of `memo://insights` resource

## Usage

### With Claude Desktop

#### Using uv
```json
"mcpServers": {
  "sqlite": {
    "command": "uv",
    "args": [
      "--directory",
      "parent_of_servers_repo/servers/src/sqlite",
      "run",
      "mcp-server-sqlite",
      "--db-path",
      "~/test.db"
    ]
  }
}
```

#### Using Docker
```json
"mcpServers": {
  "sqlite": {
    "command": "docker",
    "args": [
      "run",
      "--rm",
      "-i",
      "-v",
      "mcp-test:/mcp",
      "mcp/sqlite",
      "--db-path",
      "/mcp/test.db"
    ]
  }
}
```

### With VS Code

#### Quick installation via buttons (not shown in JSON)

#### Manual installation for settings.json
```json
{
  "mcp": {
    "inputs": [
      {
        "type": "promptString",
        "id": "db_path",
        "description": "SQLite Database Path",
        "default": "${workspaceFolder}/db.sqlite"
      }
    ],
    "servers": {
      "sqlite": {
        "command": "uvx",
        "args": [
          "mcp-server-sqlite",
          "--db-path",
          "${input:db_path}"
        ]
      }
    }
  }
}
```

#### Manual installation for .vscode/mcp.json
```json
{
  "mcp": {
    "inputs": [
      {
        "type": "promptString",
        "id": "db_path",
        "description": "SQLite Database Path (within container)",
        "default": "/mcp/db.sqlite"
      }
    ],
    "servers": {
      "sqlite": {
        "command": "docker",
        "args": [
          "run",
          "-i",
          "--rm",
          "-v",
          "mcp-sqlite:/mcp",
          "mcp/sqlite",
          "--db-path",
          "${input:db_path}"
        ]
      }
    }
  }
}
```

## Building

```bash
docker build -t mcp/sqlite .
```

## Testing with MCP inspector

```bash
uv add "mcp[cli]"
mcp dev src/mcp_server_sqlite/server.py:wrapper
```

## License

This MCP server is licensed under the MIT License. This means you are free to use, modify, and distribute the software, subject to the terms and conditions of the MIT License. For more details, please see the LICENSE file in the project repository.
