# ClickTime MCP Server

## Overview
ClickTime MCP Server is a Model Context Protocol (MCP) server integration that connects ClickTime’s time and expense tracking platform to compatible MCP-enabled applications. It allows you to access ClickTime operations (e.g., time and expense tracking workflows) directly from your chat client or other MCP-aware tools.

- **Category:** Business & Commerce – MCP Servers  
- **Integration type:** MCP Server (static endpoint)  
- **Base URL:** `https://mcp.pipedream.net/v2`

## Features
- **Time and expense tracking integration**  
  - Exposes ClickTime time and expense tracking capabilities through MCP.
- **Static MCP server URL**  
  - Uses a single static endpoint (`https://mcp.pipedream.net/v2`) for all clients.  
  - Authentication is handled when adding the server to your MCP-compatible application.
- **Account connection flow**  
  - Connect your ClickTime account through the Pipedream-hosted configuration.  
  - Select a client (where applicable) during setup.
- **MCP client compatibility**  
  - Can be added to various chat or MCP-enabled clients by configuring the server URL.  
  - Documentation is available via a configuration page (on Pipedream) describing per-client setup.
- **Tool-based operations**  
  - Provides a set of “tools” (actions) within MCP for interacting with ClickTime (the UI indicates “Available tools / Loading actions…”).  
  - Tools are discovered dynamically by MCP clients from the server.
- **Hosted by Pipedream**  
  - The MCP server is operated via Pipedream’s infrastructure, with standard terms and privacy policy.

## Configuration
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Setup steps (high-level):**
  1. Connect your ClickTime account via the Pipedream-hosted ClickTime MCP configuration page.  
  2. Copy the MCP server URL.  
  3. Add the server URL to your MCP-compatible app or chat client.  
  4. Authenticate when prompted by your client.

## Pricing
The provided content does not include any pricing or plan information for the ClickTime MCP Server integration.