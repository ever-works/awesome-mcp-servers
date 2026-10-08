# Postgres MCP Pro

Postgres MCP Pro is an open-source Model Context Protocol (MCP) server built to support you and your AI agents throughout the entire development process—from initial coding, through testing and deployment, and to production tuning and maintenance.

## Features

- **Database Health** - analyze index health, connection utilization, buffer cache, vacuum health, sequence limits, replication lag, and more.
- **Index Tuning** - explore thousands of possible indexes to find the best solution for your workload, using industrial-strength algorithms.
- **Query Plans** - validate and optimize performance by reviewing EXPLAIN plans and simulating the impact of hypothetical indexes.
- **Schema Intelligence** - context-aware SQL generation based on detailed understanding of the database schema.
- **Safe SQL Execution** - configurable access control, including support for read-only mode and safe SQL parsing, making it usable for both development and production.

## Supported Transports
- Standard Input/Output (stdio)
- Server-Sent Events (SSE)

## Installation Options

### Docker
```bash
docker pull crystaldba/postgres-mcp
```

### Python (pipx)
```bash
pipx install postgres-mcp
```

### Python (uv)
```bash
uv pip install postgres-mcp
```

## Configuration Examples

### Docker with Unrestricted Access
```json
{
  "mcpServers": {
    "postgres": {
      "command": "docker",
      "args": [
        "run",
        "-i",
        "--rm",
        "-e",
        "DATABASE_URI",
        "crystaldba/postgres-mcp",
        "--access-mode=unrestricted"
      ],
      "env": {
        "DATABASE_URI": "postgresql://username:password@localhost:5432/dbname"
      }
    }
  }
}
```

### SSE Transport
```bash
docker run -p 8000:8000 \
  -e DATABASE_URI=postgresql://username:password@localhost:5432/dbname \
  crystaldba/postgres-mcp --access-mode=unrestricted --transport=sse
```

## MCP Tools Provided

- `list_schemas`
- `list_objects`
- `get_object_details`
- `execute_sql`
- `explain_query`
- `get_top_queries`
- `analyze_workload_indexes`
- `analyze_query_indexes`
- `analyze_db_health`

## Prerequisites
- Access credentials for your PostgreSQL database.
- Docker or Python 3.12 or higher.

For index tuning and comprehensive performance analysis, the `pg_stat_statements` and `hypopg` extensions are recommended.

## Access Modes
- **Unrestricted Mode**: Full read/write access (development).
- **Restricted Mode**: Read-only transactions with resource constraints (production).
