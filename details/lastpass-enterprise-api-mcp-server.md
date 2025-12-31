# LastPass Enterprise API MCP Server

## Overview
The LastPass Enterprise API MCP Server is an MCP-compatible endpoint that allows applications and agents to interact with LastPass Enterprise, enabling secure access to enterprise password management features through a standardized MCP server URL.

- **Name:** LastPass Enterprise API MCP Server  
- **Category:** Security / MCP Servers  
- **Tags:** password-manager, security, enterprise  
- **Provider / Platform:** Pipedream Connect  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server:** Exposes the LastPass Enterprise API as an MCP server endpoint, usable by MCP-compatible chat or agent clients.
- **Static server URL:** Uses a single static URL (`https://mcp.pipedream.net/v2`) that works across supported clients.
- **Enterprise password management integration:** Designed to interact with LastPass Enterprise features for managing passwords and related security data (as provided by the underlying LastPass Enterprise API).
- **Authentication at client setup:** Authentication occurs when adding the server to your application or chat client.
- **Multi-client support:** Can be added to various chat or agent clients via their MCP configuration.

## Configuration
- **Server URL to configure in clients:**
  ```
  https://mcp.pipedream.net/v2
  ```
- **Setup:** Add this URL as an MCP server in your chat or agent application and complete authentication during setup.

## Pricing
- Not specified in the provided content.