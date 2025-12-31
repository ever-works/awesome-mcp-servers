# Altiria MCP Server

## Overview
Altiria MCP Server is an MCP-compatible integration that connects Altiria’s SMS platform to MCP clients, enabling applications and chat-based tools to send and manage SMS messages programmatically via a unified MCP server endpoint.

- **Provider / Brand:** Pipedream
- **Category:** Messaging MCP servers
- **Use cases:** SMS sending, message notifications, communication workflows
- **MCP server base URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible SMS integration**  
  - Exposes Altiria’s SMS capabilities through the Model Context Protocol (MCP), allowing any MCP client to interact with the SMS platform.

- **Static server URL for all clients**  
  - Single MCP server endpoint: `https://mcp.pipedream.net/v2` used across different MCP clients.  
  - Authentication is handled when adding/configuring the server in each client, not by changing the URL.

- **Altiria account connection**  
  - Requires connecting an Altiria account within Pipedream to enable SMS operations.  
  - Once connected, you can select the desired client / configuration to start using the server.

- **Tool-based actions (MCP tools)**  
  - Provides a set of “tools” (MCP actions) that can be invoked by MCP clients (e.g., for sending SMS, possibly managing messages or related operations).  
  - Tools are discovered dynamically by clients as “available tools” from the MCP server.

- **Multi-client support**  
  - Designed to be added to different chat or MCP-aware clients using the same server URL.  
  - Per-client configuration guides are available via the configuration page.

- **Configuration documentation**  
  - Dedicated configuration page (linked from the app) explaining how to add and authenticate the server in various clients.

## Pricing
Pricing information is not provided in the available content. Use of Altiria MCP Server may involve:
- Pipedream platform usage or plan requirements, and
- Altiria SMS service costs (message/SMS fees),
which should be confirmed on the respective provider sites.