# Beekeeper MCP Server

Beekeeper MCP Server exposes Beekeeper’s frontline workforce communication and productivity platform to MCP-compatible clients via a static MCP server URL.

## Overview
- **Type:** MCP server integration
- **Platform:** Beekeeper (frontline workforce communication & productivity)
- **Purpose:** Provide a single connection point to Beekeeper’s messaging and productivity tools from MCP-enabled applications.
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Single MCP Endpoint**  
  - Uses a static MCP server URL (`https://mcp.pipedream.net/v2`) for all clients.  
  - Authentication occurs when adding/configuring the server in your MCP-compatible application.

- **Frontline Workforce Communication Integration**  
  - Connects MCP clients to Beekeeper’s mobile communications platform, designed for frontline workers.  
  - Provides access (via MCP) to Beekeeper messaging and related tools (specific tools are listed as “Available tools” within the configuration UI, but not enumerated in the provided content).

- **Productivity & Operations**  
  - Integrates Beekeeper tools intended to increase workforce productivity, agility, and safety through a single point of contact.  
  - Centralizes communication and tools within MCP-enabled workflows.

- **Client-Agnostic Setup**  
  - Works with multiple MCP-compatible chat or AI clients.  
  - Each client can follow tailored setup steps (select client and follow “Add the server to your app” instructions).

- **Configuration Page**  
  - A dedicated configuration page (linked as “Configuration page”) provides full setup details and lists available tools and actions once loaded.

## Setup
1. **Connect Beekeeper Account**  
   - Configure Beekeeper within the Pipedream/Beekeeper MCP interface.  
   - The interface checks and validates your account.

2. **Copy MCP Server URL**  
   - Use `https://mcp.pipedream.net/v2` as the server URL in your MCP client.

3. **Add Server to MCP Client**  
   - In your chat/AI client, add a new MCP server using the static URL.  
   - Authenticate when prompted.  
   - Optionally review additional configuration steps on the full configuration page.

## Pricing
The provided content does not list any pricing or plan information for the Beekeeper MCP Server.