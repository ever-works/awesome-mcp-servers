# Bridge MCP Server

An MCP server that connects to Bridge’s Open Banking platform so MCP tools can access and work with open banking data and services.

## Overview
- **Type:** MCP server / integration
- **Category:** Finance & Market Data MCP Servers
- **Provider / Brand:** Bridge (delivered via Pipedream Connect)
- **Purpose:** Enable chat clients and MCP-compatible applications to access and work with open banking data and services exposed by Bridge’s Open Banking platform.

## Features
- **Bridge Open Banking integration**
  - Connects MCP tools to Bridge’s Open Banking platform.
  - Provides access to open banking data and services via MCP.
- **Standard MCP endpoint**
  - Static server URL for all clients: `https://mcp.pipedream.net/v2`.
  - Authentication occurs when adding the server to an application (per-client auth).
- **Multi-client compatibility**
  - Designed to be added to various MCP-compatible chat clients / apps.
  - Works as a shared, static server URL across clients.
- **Central configuration docs**
  - Usage and setup guided via a dedicated configuration page (linked as “Configuration page”).
- **Hosted by Pipedream Connect**
  - Runs on Pipedream’s managed infrastructure.
  - Benefits from Pipedream terms, privacy, and cookie policy framework.

## Usage
- Add the MCP server to an MCP-compatible chat client or application.
- Use the static URL `https://mcp.pipedream.net/v2` when configuring the server.
- Authenticate during the add/connect step as required by the platform/client.

## Pricing
- Not specified in the provided content.

## Links
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Configuration page:** /configuration (relative to host)
- **Pipedream Connect:** https://pipedream.com/connect
- **Terms:** https://pipedream.com/terms
- **Privacy Policy:** https://pipedream.com/privacy