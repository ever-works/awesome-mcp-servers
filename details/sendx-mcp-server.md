# SendX MCP Server

## Overview
SendX MCP Server is an MCP (Model Context Protocol) server integration for SendX, an email marketing platform used for sending campaigns, building subscriber lists, and automating marketing workflows. It is hosted by Pipedream and exposes SendX functionality to compatible MCP-enabled applications.

- **Category:** Business & Commerce – MCP Servers
- **Platform:** SendX (email marketing)
- **Integration host:** Pipedream
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### Email Marketing & Campaigns
- Connects an MCP-compatible application to SendX’s email marketing capabilities.
- Supports sending and managing email campaigns (via SendX’s underlying platform).

### List Building
- Provides access (through MCP) to SendX features used for building and managing contact lists.

### Marketing Automation
- Integrates SendX’s marketing automation features so they can be invoked as MCP tools/actions from supported clients.

### MCP Integration & Configuration
- **Static MCP server URL:**
  - Single static URL (`https://mcp.pipedream.net/v2`) used for all clients.
  - Authentication occurs when adding the server to an application.
- **Client-agnostic setup:**
  - Works with multiple chat or MCP-enabled clients.
  - Documentation available per client type (via Pipedream configuration pages).
- **Tool discovery:**
  - Exposes “available tools” (actions) dynamically to connected clients.

## Usage
1. **Copy the MCP server URL:** `https://mcp.pipedream.net/v2`.
2. **Add the server to your MCP-compatible app or chat client.**
3. **Authenticate** with your SendX/Pipedream account as prompted.
4. **Use available tools/actions** within your client to interact with SendX for campaigns, list management, and automation.

## Pricing
No pricing information is provided in the available content.