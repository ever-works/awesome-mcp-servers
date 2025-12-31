# Square MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Square  
**Website/Source:** https://github.com/square/square-mcp-server

## Overview
Square MCP Server is an open-source Model Context Protocol (MCP) server that exposes Square’s commerce and payments APIs over MCP. It is hosted at `https://mcp.squareup.com/sse` and uses OAuth 2.1 for authentication, enabling AI agents or MCP-compatible clients to interact with Square’s payments and commerce capabilities.

## Features
- **MCP-compatible server**
  - Implements the Model Context Protocol to integrate with MCP clients.
  - Provides a server endpoint at `https://mcp.squareup.com/sse`.

- **Square commerce and payments integration**
  - Connects to Square’s commerce and payments APIs.
  - Designed to let MCP clients perform operations related to payments and point-of-sale / e-commerce workflows (specific endpoints and operations depend on the underlying Square APIs).

- **OAuth 2.1 authentication**
  - Uses OAuth 2.1 for secure authorization to Square accounts.
  - Allows delegated access to Square resources without sharing credentials.

- **Open-source implementation**
  - Source code available on GitHub under the Apache-2.0 license.
  - TypeScript-based codebase (`index.ts`, `config.ts`, `api-types.ts`, `services/`, `utils/`).
  - Includes testing configuration via Jest (`jest.config.js`).

- **Configurable and modular structure**
  - `config.ts` suggests environment-based configuration (e.g., API keys, OAuth settings, endpoints).
  - `services/` and `utils/` directories indicate separation of concerns for API service logic and helper utilities.

## Authentication
- Uses **OAuth 2.1** to authorize access to Square APIs via the MCP server.
- Intended for secure integration of Square accounts with MCP clients.

## Licensing
- Licensed under the **Apache-2.0** license.

## Pricing
- No pricing information is provided in the repository content. The MCP server itself is open source; any costs would depend on Square’s underlying API and account pricing, which is not detailed here.