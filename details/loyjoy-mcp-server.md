# LoyJoy MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** LoyJoy  
**Source:** https://mcp.pipedream.com/app/loyjoy

## Overview
LoyJoy MCP Server connects the LoyJoy conversational marketing platform to MCP-compatible applications. It exposes LoyJoy’s conversational capabilities as tools that can be called from your chat client or agent environment, enabling customer engagement and marketing workflows through a standard MCP endpoint.

## Features
- **Standard MCP Endpoint**  
  - Uses a single static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL works across different LoyJoy clients / accounts.

- **Account Integration**  
  - Connects to a LoyJoy account via the Pipedream interface.  
  - Allows selecting the appropriate client after authentication.

- **Tooling Exposure**  
  - Exposes LoyJoy “tools” (actions) to MCP-compatible chat clients.  
  - Tools are auto-loaded / discovered by the MCP server once configured.

- **Client-Agnostic Setup**  
  - Can be added to multiple chat clients that support MCP.  
  - Configuration guidance available per chat client (via the app’s configuration page).

- **Hosted by Pipedream**  
  - MCP server is operated through Pipedream’s infrastructure.  
  - Uses Pipedream’s configuration and connection flow for setup.

## Use Cases
- Integrate LoyJoy’s conversational marketing flows into MCP-based chat agents.  
- Trigger LoyJoy customer engagement and conversion actions directly from an MCP client.  
- Centralize conversational marketing tools behind a single MCP endpoint.

## Configuration
1. Connect your LoyJoy account in the Pipedream LoyJoy MCP app.  
2. Select the desired LoyJoy client.  
3. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
4. Add this server URL to your MCP-compatible application and authenticate when prompted.  
5. Use the available LoyJoy tools exposed through the MCP server.

## Pricing
The provided content does not include any pricing or plan information for the LoyJoy MCP Server or its usage via Pipedream.