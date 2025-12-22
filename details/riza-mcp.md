# Riza MCP

## Overview
Riza MCP is an MCP server that wraps the [Riza](https://riza.io) API and exposes it as tools for LLMs. It provides an isolated code interpreter and arbitrary code execution / tool-use platform for LLM-generated code, implemented in TypeScript.

Repository: <https://github.com/riza-io/riza-mcp>

## Features
- **Isolated code interpreter for LLMs**
  - Runs LLM-generated code in an isolated environment via the Riza API.
- **MCP server implementation**
  - Presents Riza API endpoints as Model Context Protocol (MCP) tools.
- **Tool-based interaction model**
  - Exposes Riza functionality as discrete tools that can be invoked by LLMs.
- **TypeScript implementation**
  - Server logic provided in a TypeScript codebase.
- **Configurable with MCP clients**
  - Designed to work with Claude Desktop and other MCP-compatible clients (via configuration of the MCP server and Riza API key).

## Exposed Tools
The Riza MCP server provides these tools to the LLM:
- `create_tool` – create new tools via the Riza API.
- `execute_tool` – execute an existing Riza tool (listed multiple times in source but functionally one capability).
- `fetch_tool` – retrieve details for an existing tool.
- `edit_tool` – modify an existing tool.
- `list_tools` – list available tools.
- `execute_code` – execute arbitrary code in the isolated Riza interpreter environment.

## Integrations
- **Riza API** – core execution and tool platform behind the MCP server.
- **Claude Desktop** – can be configured as an MCP client to use Riza MCP.
- **Other MCP clients** – usable with any client that supports the Model Context Protocol, via appropriate configuration.

## Requirements
- Riza API key (obtainable from the Riza Dashboard) for the MCP server to call the Riza API.

## Pricing
- The repository indicates that you can obtain a free Riza API key from the Riza Dashboard.
- No detailed pricing plans or tiers are specified in the provided content; refer to the Riza service for current pricing information on API usage.