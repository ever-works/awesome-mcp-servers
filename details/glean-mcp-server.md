# Glean MCP Server

**Category:** MCP server directories & lists  
**Brand:** Glean  
**Repository:** https://github.com/longyi1207/glean-mcp-server  
**Slug:** `glean-mcp-server`

## Overview
Glean MCP Server is an open-source Model Context Protocol (MCP) server that integrates with the Glean API to provide search and chat capabilities (including enterprise search) as MCP tools, suitable for use with MCP-compatible clients like Claude Desktop.

## Features
- Implements an MCP server for Glean
- Integrates directly with the Glean API
- Exposes Glean Search functionality as MCP tools
- Exposes Glean Chat functionality as MCP tools
- Designed to work with Claude Desktop via MCP configuration
- Docker-based deployment supported (Dockerfile included)
- Implemented in TypeScript (`index.ts`, `tsconfig.json`)
- Configurable via environment variables:
  - `GLEAN_API_KEY` – Glean API authentication
  - `GLEAN_DOMAIN` – Glean instance/domain configuration

## Setup & Usage
- Build the Docker image from the provided `Dockerfile`.
- Configure Claude Desktop (or another MCP client) to use the server, for example in `claude_desktop_config.json`:
  - Command: `docker`
  - Args (example):
    - `run`, `-i`, `--rm`
    - `-e`, `GLEAN_API_KEY`
    - `-e`, `GLEAN_DOMAIN`
    - `glean-server` (image name)
  - Environment variables:
    - `GLEAN_API_KEY`: `YOUR_API_KEY_HERE`
    - `GLEAN_DOMAIN`: `YOUR_DOMAIN_HERE`

## Pricing
- Pricing is not specified in the repository.  
- The MCP server implementation itself is open-source (MIT License).  
- Access to the Glean API may require a separate Glean account or subscription.

## License
- Licensed under the **MIT License**.  
- Permits use, modification, and distribution subject to MIT terms (see `LICENSE` in the repository for details).