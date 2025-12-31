# Frontify MCP Server

**Category:** Content Management MCP Servers  
**Vendor:** Frontify / Pipedream  
**Website:** https://mcp.pipedream.com/app/frontify

## Overview
Frontify MCP Server is an MCP (Model Context Protocol) server integration that connects applications to Frontify, a brand management platform where brand assets and guidelines are stored. It enables MCP-based workflows to interact with Frontify content from compatible chat or AI clients.

## Features
- **MCP server endpoint**  
  - Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
  - URL is added to any MCP-compatible application as a server endpoint.

- **Frontify account connection**  
  - Connects to a Frontify account via the Pipedream-hosted integration.  
  - Lets you select the appropriate Frontify client/workspace after authentication.

- **App integration flow**  
  - Designed to be added to supported chat / AI clients that use MCP.  
  - Configuration instructions available via a dedicated configuration page.

- **Tool-based operations (via MCP)**  
  - Exposes Frontify-related actions as MCP “tools” (the interface indicates “Available tools” and “Loading actions…”), allowing applications to trigger Frontify operations programmatically.  
  - The exact tool list is loaded dynamically from the server at runtime.

## Usage
1. Connect your Frontify account within the Pipedream Frontify MCP page.  
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add this MCP server URL to your MCP-compatible application or chat client.  
4. Authenticate when prompted and select your Frontify client/workspace.

## Pricing
The provided content does not list any pricing or plans for the Frontify MCP Server integration.