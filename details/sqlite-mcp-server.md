# SQLite MCP Server

**Category:** Database MCP Servers  
**Brand:** SQLite  
**Source:** https://github.com/prayanks/mcp-sqlite-server

## Overview
SQLite MCP Server provides Model Context Protocol (MCP) server implementations for interacting with SQLite databases from an MCP-compatible client. It includes both SDIO and SSE variants, enabling database access and basic querying/analysis workflows against SQLite databases.

## Features
- **MCP server for SQLite**
  - Exposes a SQLite database to MCP-compatible clients.
  - Designed for database interaction and business-intelligence-style querying.

- **Two implementation modes**
  - **SDIO implementation** via `sqlite_sdio_mcp_server.py`.
  - **SSE implementation** via `sqlite_sse_mcp_server.py`.

- **SQLite database integration**
  - Uses standard SQLite `.db` files.
  - Includes a sample `startups.db` database in the repository for testing.

- **Sample configuration and utilities**
  - `claude_desktop_config.json.sample` for example MCP client configuration.
  - `create_sample_db.py` for generating a sample SQLite database.
  - `install_sdio.py` helper script for installing / wiring up the SDIO server.

- **Open-source licensing**
  - Released under the MIT License.

## Pricing
- Not specified in the available content. The project is open source under the MIT License and can be used accordingly.