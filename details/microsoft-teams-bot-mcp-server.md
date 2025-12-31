# Microsoft Teams Bot MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Microsoft  
**Slug:** `microsoft-teams-bot-mcp-server`

## Overview
Microsoft Teams Bot MCP Server exposes a custom Microsoft Teams bot user via the Model Context Protocol (MCP). It allows MCP-aware tools and clients to interact with Teams through that bot for automated messaging, command handling, and other bot-based workflows.

Source: https://mcp.pipedream.com/app/microsoft_teams_bot

## Features
- **MCP-based access to Microsoft Teams**  
  - Provides a static MCP server endpoint: `https://mcp.pipedream.net/v2`  
  - Usable from any compatible client that supports adding custom MCP servers.

- **Custom Teams bot user integration**  
  - Connects to a Microsoft Teams account and operates via a dedicated bot user.  
  - Enables automated interactions and responses in Teams channels and chats.

- **Client-agnostic setup**  
  - The same MCP server URL works for all supported MCP clients.  
  - Authentication is handled when the server is added to the chosen client.

- **Configuration workflow**  
  - "Configure Microsoft Teams Bot" flow to connect your Microsoft account.  
  - After connection, users select their MCP client and follow client-specific instructions.  
  - Detailed setup instructions available on a central configuration page (linked from the app).

- **Tool exposure within MCP**  
  - Designed to expose Teams-related tools/actions (e.g., messaging, command handling) via MCP so they can be called from within your MCP-aware applications.  
  - Tools are dynamically loaded by the MCP server based on your configuration.

## Pricing
The provided content does not include any pricing or plan information for Microsoft Teams Bot MCP Server.