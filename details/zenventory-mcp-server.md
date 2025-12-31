# Zenventory MCP Server

## Overview
Zenventory MCP Server exposes Zenventory’s e‑commerce inventory and operations capabilities to MCP‑compatible automation and orchestration tools. It is accessed via a static MCP server URL and can be integrated into various chat or agent clients that support the MCP protocol.

- **Category:** Business & Commerce – MCP Servers  
- **Use Case:** Automating and orchestrating e‑commerce inventory and operations workflows through MCP-compatible clients.

## Features
- **MCP-compatible server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Single URL works for all Zenventory clients; authentication handled when adding the server to your application.

- **Zenventory account connectivity**  
  - Connect a Zenventory account within Pipedream’s Zenventory MCP Server app.  
  - Select a specific Zenventory client after connection to scope operations.

- **Integration with MCP-enabled applications**  
  - Add the MCP server to supported chat / agent clients to interact with Zenventory through tools and actions.  
  - Uses MCP for structured tool invocation (e.g., inventory/operations-related actions once loaded and configured).

- **Configurable through Pipedream**  
  - Web-based configuration flow (“Configure Zenventory”) to link accounts and clients.  
  - Access to a dedicated configuration page for additional setup details.

> Note: The page references “Available tools” and “Loading actions…”, indicating multiple Zenventory-related tools/actions are exposed via MCP, but specific tool names and operations are not listed in the provided content.

## Technical Details
- **Protocol:** Model Context Protocol (MCP) server.  
- **Endpoint:** `https://mcp.pipedream.net/v2` (static, shared across clients; authentication per app).  
- **Host platform:** Pipedream MCP infrastructure.

## Pricing
The provided content does not list any pricing or plans for the Zenventory MCP Server. Pricing details would need to be obtained from Pipedream or Zenventory directly.