# mcp-server-odoo

**Category:** Business & Commerce MCP Servers  
**Brand:** ivnvxd  
**License:** MPL-2.0  
**Source:** https://github.com/ivnvxd/mcp-server-odoo

## Overview
mcp-server-odoo is a Model Context Protocol (MCP) server that connects AI assistants (such as Claude) to Odoo ERP systems. It provides standardized resources and tools for secure data access and manipulation, allowing natural-language interaction with Odoo for business data retrieval, record management, and workflow operations.

## Features
- **MCP-compliant server for Odoo**  
  - Implements the Model Context Protocol to expose Odoo functionality as standardized resources and tools.

- **Secure Odoo ERP integration**  
  - Connects to an existing Odoo instance for business data operations.  
  - Uses environment-based configuration (via `.env` as indicated by `.env.example`) for connection and credential settings.

- **Data retrieval and search**  
  - Accesses business data stored in Odoo.  
  - Searches records across Odoo models (e.g., customers, products, orders, etc. — depending on the connected Odoo instance).

- **Record creation and updates**  
  - Creates new records in Odoo via tools exposed to the AI assistant.  
  - Updates existing Odoo data using natural-language instructions routed through the MCP server.

- **Workflow and instance management hooks**  
  - Supports managing aspects of the Odoo instance (such as record lifecycle actions) through MCP tools, enabling workflow automation scenarios.

- **Configuration and environment setup**  
  - Example environment file (`.env.example`) for quickly configuring Odoo connection details.  
  - Python project defined via `pyproject.toml` for installation and dependency management.  
  - Includes tests (`tests` directory) and changelog (`CHANGELOG.md`) for version tracking.

## Technical Details
- **Language/Runtime:** Python (per `pyproject.toml` and project structure).  
- **Protocol:** Model Context Protocol (MCP) for interaction with AI assistants.  
- **Repository structure:**  
  - `mcp_server_odoo/` – core MCP server implementation for Odoo.  
  - `tests/` – automated tests.  
  - `.github/` – GitHub workflows and configuration.

## Pricing
- This is an open-source project under the MPL-2.0 license. No pricing or paid plans are specified in the provided content.