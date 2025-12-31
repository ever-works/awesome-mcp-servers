# Microsoft OneNote MCP Server

## Overview
The Microsoft OneNote MCP Server enables MCP-based interaction with Microsoft OneNote, allowing you to work with cross-functional notebooks for capturing and organizing notes directly from MCP-compatible clients.

- **Category:** Document Management MCP Servers
- **Brand:** Microsoft
- **Source URL:** https://mcp.pipedream.com/app/onenote
- **Slug:** `microsoft-onenote-mcp-server`
- **Tags:** notes, document-management, productivity

## Features
- **MCP-based OneNote integration**: Connects Microsoft OneNote as an MCP server so it can be accessed from MCP-compatible applications and chat clients.
- **Cross-functional notebooks**: Works with OneNote notebooks for capturing and organizing notes across different contexts and use cases.
- **Static MCP server URL**: Uses a single static MCP endpoint for all clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic configuration**: The same server URL works with multiple clients; authentication occurs when the server is added to the target application.
- **Account connection flow**: Requires connecting a Microsoft OneNote account via Pipedream before use.
- **Configuration guidance**: Provides client-specific setup instructions and a dedicated configuration page for adding the server to supported apps.
- **Tools/actions support**: Exposes OneNote-related tools/actions (loaded dynamically) for use within MCP clients.

## Setup
1. Connect your Microsoft OneNote account via the Pipedream interface.
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
3. Add the server URL to your MCP-compatible chat client or application.
4. Authenticate when prompted in your client.

## Pricing
Pricing information is not provided in the available content.