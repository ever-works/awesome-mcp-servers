# SQLite Cloud MCP Server

## Overview

The SQLite Cloud MCP Server enables AI models to interact with SQLite Cloud databases through the Model Context Protocol (MCP). It provides a set of tools for executing SQL queries, managing database schemas, running predefined commands, and analyzing query performance.

## Features

- **Query Execution**: Perform SELECT, INSERT, UPDATE, and DELETE SQL operations on SQLite Cloud databases.
- **Schema Management**: Create tables, list existing tables, and retrieve schema details.
- **Command Execution**: Run predefined commands supported by SQLite Cloud.
- **Performance Analysis**: Identify slow queries, analyze query plans, and reset query statistics.

## Tools

The MCP Server exposes the following tools:

- `read-query`: Perform SELECT queries and fetch results.
- `write-query`: Perform INSERT, UPDATE, or DELETE operations.
- `create-table`: Create new database tables.
- `list-tables`: Display all tables in the database.
- `describe-table`: Retrieve schema details for a specific table.
- `list-commands`: List available commands and access external documentation.
- `execute-command`: Run commands from the list-commands tool.
- `list-analyzer`: Analyze slow queries with optional filters.
- `analyzer-plan-id`: Gather details about query plans and indexes.
- `analyzer-reset`: Reset query statistics for specific queries, groups, or databases.

## Getting Started

1. Create a free account on SQLite Cloud and obtain your Connection String.
2. Ensure Node.js is installed on your machine.
3. Start the server using one of the following methods:
   - Using npx: `npx @sqlitecloud/mcp-server --connectionString <your_connection_string>`
   - After building: `node dist/main.js --connectionString <your_connection_string>`
4. Configure your AI model (e.g., in VSCode) using the provided `.vscode/mcp.json` configuration.

## Development

- Build the package: `npm run build`
- Run after building: `node dist/main.js --connectionString <CONNECTION_STRING>`
- Local testing: Pack the package with `npm pack` and run the packed file.
- Use the MCP Inspector to test stdio and sse transports.

## Requirements

- Node.js (check with `node --version`)
- A valid SQLite Cloud connection string.

## Pricing

The SQLite Cloud MCP Server is free and open-source software. Usage of SQLite Cloud may incur costs based on their pricing plans; refer to SQLite Cloud for details.

## License

This project is open-source and likely licensed under an OSI-approved license (check the repository for details).
