# WATI MCP Server

**Category:** Messaging MCP Servers  
**Slug:** `wati-mcp-server`  
**Source:** https://mcp.pipedream.com/app/wati

## Overview
WATI MCP Server is an MCP (Model Context Protocol) server integration that exposes WATI’s WhatsApp marketing and customer engagement capabilities to MCP-compatible applications. It is hosted on Pipedream and is designed for use in automated workflows and chat-based tools.

## Features
- **MCP-compatible server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Single URL works for all clients; authentication is handled when adding the server to an application.

- **WhatsApp marketing & customer engagement integration**  
  - Connects a WATI account for use within MCP-based apps and workflows.  
  - Intended for marketing and customer engagement scenarios over WhatsApp.

- **Account connection & configuration**  
  - “Configure WATI” flow to connect a WATI account.  
  - Account status checking (“Checking your account…”).  
  - Client selection step after account connection.

- **Tooling exposure via MCP**  
  - Exposes “available tools” (actions) from WATI through the MCP server (listed as “Loading actions…” / “Loading available tools…” in the UI).  
  - Designed to be used as tools within chat clients and other MCP-compatible applications.

- **Multi-client support**  
  - Instructions reference adding the server to different chat clients.  
  - Uses a single server URL with per-client authentication.

- **Central configuration documentation**  
  - Linked configuration guide via a dedicated “Configuration page” on Pipedream for setup details.

## Integration & Usage
- Add the MCP server URL `https://mcp.pipedream.net/v2` to an MCP-compatible app or chat client.
- Authenticate with WATI when prompted by the application. 
- Select the connected WATI client/account for use in workflows and tools.

## Pricing
- No pricing information is provided in the available content.