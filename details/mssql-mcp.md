# MSSQL-MCP

**Category:** Database Messaging MCP Servers  
**Brand:** daobataotie  
**Source:** https://github.com/daobataotie/mssql-mcp

## Overview

MSSQL-MCP is a Model Context Protocol (MCP) server for Microsoft SQL Server, adapted from the official SQLite MCP implementation. It exposes database operations over MCP so AI-driven tools and agents can:

- Run SQL queries against MSSQL databases
- Perform business data analysis
- Automatically generate business insight memos

## Features

### Core MCP Operations
- **read_query** – Execute read-only SQL queries against an MSSQL database and return results.
- **write_query** – Execute data modification queries (INSERT, UPDATE, DELETE, etc.).
- **create_table** – Create new tables in the target MSSQL database via MCP.
- **list_tables** – List available tables in the connected MSSQL database.
- **describe-table** – Retrieve schema/structure information for a specified table.
- **append_insight** – Append or generate business insight memos based on analyzed data.

### Data Handling & Intelligence
- Works with **non-standardized column names**; the AI layer attempts to match columns automatically.
- **Self-correction of SQL errors** during execution via AI-driven feedback and re-generation.
- Designed to support **business intelligence workflows**, including insight extraction from query results.

### Compatibility & Integration
- Adapted from the **official SQLite MCP server** to work with **Microsoft SQL Server**.
- Usable with multiple MCP-compatible tools, including (as documented examples):
  - Claude Desktop
  - Windsurf
  - Cursor (JSON-based configuration support)
  - MCP Inspector

### Project Structure
- `src/server.py` – Main MCP server implementation.
- `requirements.txt` – Python dependency list.
- `imgs/` – Screenshots and demo assets (table schema, demo usage, Cursor config).
- Multi-language documentation: `README.md`, `README_en.md`, `README_zh.md`.

### Operating Environment
- **Language:** Python 3.x
- **Required packages:** As specified in `requirements.txt`.
- **Driver:** ODBC Driver 17 for SQL Server (for database connectivity).

## Pricing

No pricing information is provided. The project is open-source under the **MIT License**.