# Unity Catalog MCP Server

## Overview
Unity Catalog MCP Server is an open‑source Model Context Protocol (MCP) server that enables LLMs to interact with Unity Catalog AI. It supports full CRUD operations on Unity Catalog Functions and exposes those functions so they can be executed as MCP tools.

- **Type:** Open‑source MCP server
- **Source:** [GitHub – ognis1205/mcp-server-unitycatalog](https://github.com/ognis1205/mcp-server-unitycatalog)
- **License:** MIT
- **Category:** Data access & integration MCP servers
- **Tags:** data-catalog, CRUD, AI-integration

## Key Capabilities
- Integrates Unity Catalog AI with tools that speak the Model Context Protocol
- Allows LLMs to manage Unity Catalog Functions via MCP
- Exposes Unity Catalog Functions as callable MCP tools for execution

## Features
- **Unity Catalog AI integration**
  - Connects to Unity Catalog AI to work with cataloged functions.
- **CRUD on Unity Catalog Functions**
  - Create Unity Catalog Functions
  - Read / list Unity Catalog Functions
  - Update existing Unity Catalog Functions
  - Delete Unity Catalog Functions
- **Execution as MCP tools**
  - Wraps Unity Catalog Functions so they are executable as MCP tools by LLM clients.
- **MCP server implementation**
  - Implements the Model Context Protocol for interoperability with MCP‑compatible clients.
- **Containerization support**
  - Includes a `Dockerfile` for running the server in containerized environments.
- **Configuration via environment**
  - Uses an `.env` file for environment‑based configuration.
- **Python project setup**
  - Managed via `pyproject.toml` and `uv.lock` for dependencies and reproducible environments.
- **Documentation and tests**
  - `docs/` directory for project documentation
  - `tests/` directory for automated tests

## Technology Stack
- Language: Python
- Distribution: pyproject/uv‑based Python project
- Deployment: Dockerfile provided for container builds

## Pricing
- **Open Source:** Available under the MIT license (no listed usage-based pricing).