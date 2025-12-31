# Wire2Air MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Wire2Air  
**Source:** https://mcp.pipedream.com/app/wire2air

## Overview
Wire2Air MCP Server is an MCP-compatible integration that exposes Wire2Air’s SMS gateway and mobile marketing APIs. It is designed to support bulk SMS campaigns, dedicated shortcodes, and 2‑way messaging inside MCP-enabled workflows and chat clients.

The server is hosted via Pipedream Connect and is accessed through a shared MCP endpoint, with authentication handled when configuring it in your client.

## MCP Server URL
- Static MCP endpoint (for all clients):
  - `https://mcp.pipedream.net/v2`
- Authentication is configured when adding the server to your MCP-compatible application or chat client.

## Features
- **SMS Gateway Access**  
  - Connects to Wire2Air’s SMS gateway through MCP.  
  - Enables sending SMS from MCP workflows and chat clients.

- **Bulk SMS**  
  - Supports high‑volume / bulk SMS sending for campaigns and notifications.  
  - Suitable for marketing blasts, alerts, and other mass messaging scenarios.

- **Mobile Marketing APIs**  
  - Surfaces Wire2Air’s mobile marketing APIs to MCP.  
  - Can be used to build marketing and engagement workflows within MCP-enabled tools.

- **Dedicated Shortcodes**  
  - Supports use of dedicated SMS shortcodes for campaigns and brand-specific messaging.

- **2‑Way Messaging (2‑Way API)**  
  - Enables interactive SMS experiences where users can both receive and reply to messages.  
  - Allows MCP workflows to react to inbound SMS, opt-ins, and other user responses.

- **MCP Workflow Integration**  
  - Designed to be added as a server in compatible chat clients and agents.  
  - Lets LLM agents trigger SMS actions and respond to SMS events as part of a broader workflow.

- **Static Endpoint for All Clients**  
  - Uses a single static `https://mcp.pipedream.net/v2` endpoint for all clients.  
  - Configuration differences are handled via authentication and client-side setup.

## Integration & Configuration
- Add the MCP server to your compatible chat client or MCP runtime using the static URL.  
- Configure authentication when registering the server in your application.  
- Additional configuration details are available on the provider’s Configuration page (not reproduced here).

## Pricing
The provided content does not list any pricing or plan details for the Wire2Air MCP Server or the underlying Wire2Air services.