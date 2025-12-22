# OpenRPC MCP Server

A Model Context Protocol (MCP) server for discovering and interacting with JSON-RPC APIs defined via OpenRPC specifications, exposing them as tools to AI clients.

## Features
- Implements a Model Context Protocol (MCP) server interface.
- Provides JSON-RPC functionality based on OpenRPC specifications.
- Exposes OpenRPC-defined JSON-RPC APIs as MCP tools for AI assistants.
- Tooling:
  - `rpc_call` – perform JSON-RPC calls against the configured OpenRPC API.
  - `rpc_discover` – discover available JSON-RPC methods and schema information.
  - `rpc.discover` – alternate discovery tool for enumerating RPC capabilities.
- Designed to integrate with MCP-aware clients such as Claude Desktop.

## Installation & Integration
- Can be configured as an MCP server in Claude Desktop.
- Claude Desktop configuration paths:
  - macOS: `~/Library/Application Support/Claude/claude_desktop_config.json`
  - Windows: `%APPDATA%/Claude/claude_desktop_config.json`

## Development & Debugging
- Repository includes scripts and configuration for local development and building the server (see `README.md` and `package.json` in the repo).
- Uses stdio for MCP communication.
- Supports debugging via the **MCP Inspector**: the inspector provides a browser-based interface for inspecting and debugging MCP interactions.

## Pricing
- Free and open-source (see the `LICENSE` file in the repository for licensing details).