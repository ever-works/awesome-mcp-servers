# FastAPI to MCP auto generator

## Overview
FastAPI to MCP auto generator is an open-source tool that exposes existing FastAPI endpoints as Model Context Protocol (MCP) tools with minimal or zero additional configuration. It enables rapid creation of MCP servers from FastAPI applications, including support for authentication.

- **Type:** Open-source library / development tool
- **Ecosystem:** FastAPI, MCP
- **License:** MIT
- **Source:** https://github.com/tadata-org/fastapi_mcp

## Features
- **Automatic MCP tool generation**
  - Converts existing FastAPI endpoints into MCP tools.
  - Designed for zero or minimal configuration on top of a standard FastAPI app.

- **MCP server creation**
  - Allows using a FastAPI application as an MCP server.
  - Integrates with the Model Context Protocol so endpoints become callable tools from MCP-compatible clients.

- **Authentication support**
  - Exposes FastAPI endpoints as MCP tools “with Auth,” leveraging FastAPI’s auth mechanisms when used via MCP.

- **FastAPI integration**
  - Built specifically for FastAPI applications.
  - Uses FastAPI’s existing routing and dependency system as the basis for MCP tools.

- **Developer-focused project structure**
  - Includes `examples` directory to demonstrate usage patterns.
  - Includes `docs` directory for additional documentation.
  - Test suite under `tests` directory for reliability and regression checks.
  - Configuration and tooling files for development quality (pre-commit, coverage, etc.).

## Pricing
- **Open Source**
  - License: MIT
  - Cost: Free to use, modify, and self-host under the terms of the MIT license.