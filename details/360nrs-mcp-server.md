# 360NRS MCP Server

## Overview
The 360NRS MCP Server is an MCP Server integration that connects 360NRS multichannel marketing capabilities with MCP-compatible applications (such as chat clients) via Pipedream. It enables SMS, email, WhatsApp, and interactive voice campaign operations through a unified MCP endpoint.

## Features
- **Multichannel marketing integration**
  - SMS marketing operations
  - Email marketing operations
  - WhatsApp-based marketing and messaging
  - Interactive voice campaign operations
- **MCP protocol support**
  - Exposes 360NRS marketing capabilities via the MCP protocol
  - Designed to be added as a server to MCP-compatible apps (e.g., chat clients)
- **Static MCP server endpoint**
  - Single static URL for all clients: `https://mcp.pipedream.net/v2`
  - Authentication handled when adding the server to the client/application
- **Pipedream-hosted**
  - Operates through Pipedream Connect infrastructure
  - Centralized configuration available via Pipedream’s configuration page

## Setup
1. **Copy MCP server URL**  
   Use `https://mcp.pipedream.net/v2` as the server URL.
2. **Add to your application**  
   - Add the MCP server URL in your chat client or other MCP-compatible app.  
   - Authenticate as prompted by the client during setup.
3. **Configure behavior**  
   - Adjust configuration options via the Pipedream Configuration page (as provided by your client / Pipedream UI).

## Pricing
Pricing details are not specified in the provided content. Refer to the 360NRS or Pipedream websites for current pricing information.