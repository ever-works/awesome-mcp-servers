# Polygon MCP Server

**Category:** Finance & Market Data MCP Servers  
**Brand:** polygonio  
**Source:** https://mcp.pipedream.com/app/polygon

## Overview
The Polygon MCP Server exposes Polygon.io stock market data APIs to MCP-compatible clients, enabling programmatic access to financial market data within chat-based or other MCP-enabled applications.

## Features
- **MCP Server Endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Single endpoint intended to work with all supported MCP clients.

- **Polygon Stock Market Data Access**  
  - Integrates with Polygon.io’s stock market data APIs (e.g., for equities and related market data).  
  - Designed for use in web and app development contexts that require market data.

- **Client Integration**  
  - Can be added as an MCP server to compatible chat clients and applications.  
  - Workflow: connect a Polygon account via Pipedream, then configure the MCP client to use the static server URL.  
  - Configuration help available via a dedicated configuration page (outside the provided content).

- **Account-Linked Operation**  
  - Requires connecting your Polygon account before use.  
  - Authentication occurs when adding the server to your application, not by changing the server URL.

- **Tooling Exposure**  
  - Exposes “tools” (actions) from Polygon’s APIs to MCP clients (the specific tools are not listed in the provided content but are surfaced dynamically once configured).

## Authentication
- Uses a static MCP server URL with per-account authentication applied when the server is added to a client or application.

## Pricing
- No pricing details are provided in the available content. Use of this MCP server may depend on Polygon.io’s own API pricing and any associated Pipedream terms, which are not specified here.