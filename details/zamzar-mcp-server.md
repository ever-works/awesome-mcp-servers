# Zamzar MCP Server

An MCP server integration for Zamzar’s online file conversion services, provided via Pipedream Connect.

## Overview
- **Type:** MCP server (Model Context Protocol server)
- **Purpose:** Enable MCP-compatible clients to perform online file conversions using Zamzar’s conversion services.
- **Provider / Host:** Pipedream Connect
- **Category:** File management / document conversion
- **Endpoint URL:** `https://mcp.pipedream.net/v2`

## Features
- **Online file conversion via Zamzar**  
  - Uses Zamzar’s conversion services to convert files between different formats.
- **MCP-compatible server**  
  - Designed to be added as a server within any client that supports the Model Context Protocol (MCP).
- **Single static server URL**  
  - Uses a unified, static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL works across different MCP clients.
- **Authentication at client setup**  
  - Authentication occurs when adding the MCP server to your application/client.
- **Client-agnostic setup**  
  - Can be used with multiple chat or MCP clients; setup instructions available per client type (via the configuration page on the source site).

## Configuration
- **Server URL to add in MCP clients:**  
  `https://mcp.pipedream.net/v2`
- **Setup guidance:**  
  - Choose your chat/MCP client and follow its instructions to add the server (details hosted on the configuration page at the source site).

## Pricing
- Not specified on the provided page. Pricing and usage limits, if any, would be determined by Pipedream and/or Zamzar and are not detailed in the given content.