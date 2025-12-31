# MariaDB MCP Server

A Python-based MCP server that integrates with MariaDB to expose database schema information and enable secure, read-only querying via the Model Context Protocol.

---

## Overview

- **Type**: MCP (Model Context Protocol) server
- **Ecosystem**: MariaDB, Python
- **Use Case**: Retrieve data and schema details from a MariaDB database for tools/agents that speak MCP (e.g., Claude Desktop).
- **License**: MIT

---

## Features

### MCP Resources
- **Schema exposure**
  - Exposes the list of schemas in the configured MariaDB database as MCP resources.

### MCP Tools
- **`query_database` tool**
  - Executes read-only SQL operations against a MariaDB database.
  - Intended for safe data retrieval (no write/DDL operations).

### Configuration & Integration
- **Claude Desktop integration**
  - Can be configured as an MCP server in Claude Desktop via `claude_desktop_config.json`.
  - Supports published server mode using `uvx` as the command.
  - Supports development/unpublished server mode using `uv` with a local source directory.
- **Connection parameters**
  - Host (`--host` / `MARIADB_HOST`)
  - Port (`--port` / `MARIADB_PORT`)
  - User (`--user` / `MARIADB_USER`)
  - Password (`--password` / `MARIADB_PASSWORD`)
  - Database name (`--database` / `MARIADB_DATABASE`)

### Environment-Based Configuration (Dev Mode)
- Uses environment variables for connection details in development/unpublished setups:
  - `MARIADB_HOST`
  - `MARIADB_USER`
  - `MARIADB_PASSWORD`
  - `MARIADB_DATABASE`
  - `MARIADB_PORT`

### Platform-Specific Notes (macOS)
- Requires MariaDB Connector/C for the `mariadb_config` utility.
- If `OSError: mariadb_config not found` occurs, it can be resolved by installing and exposing `mariadb-connector-c` on `PATH` and setting `MARIADB_CONFIG`.

---

## Installation & Dependencies

### MariaDB & Connector/C (macOS)
- Install MariaDB Connector/C (example with Homebrew):
  - `brew install mariadb-connector-c`
  - Add to `PATH`, e.g.: `export PATH="/opt/homebrew/opt/mariadb-connector-c/bin:$PATH"`
  - Set `MARIADB_CONFIG`, e.g.: `export MARIADB_CONFIG=$(brew --prefix mariadb-connector-c)/bin/mariadb_config`
- After resolving `mariadb_config`, install the Python dependency:
  - `uv add mariadb`

*(Repository documentation should be consulted for full, up-to-date install steps.)*

---

## Pricing

- Not specified in the provided content.
- Repository is MIT licensed, which typically indicates free/open-source usage, subject to MIT license terms.