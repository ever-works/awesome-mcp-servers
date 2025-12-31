# RealGeeks MCP Server

## Overview
The RealGeeks MCP Server connects the RealGeeks real estate CRM and conversion engine to MCP‑compatible applications via Pipedream. It enables you to integrate RealGeeks lead generation and client management workflows into chat clients and other tools using a single MCP server endpoint.

## Features
- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same endpoint can be used for all clients; authentication is handled when adding the server to your application.

- **RealGeeks CRM integration**  
  - Connects to a RealGeeks account through Pipedream.  
  - Lets you select and configure a specific RealGeeks client/account once connected.

- **Configuration via Pipedream UI**  
  - Guides you to connect your RealGeeks account.  
  - Provides a configuration page for more detailed setup instructions.  
  - Supports adding the MCP server to different chat clients, with client-specific getting-started instructions.

- **Tooling exposure (via MCP)**  
  - Exposes RealGeeks-related tools / actions as MCP tools once the server is connected (exact tools are dynamically loaded in the UI).  
  - Designed to plug into automation workflows and chat-based applications.

## Setup
1. Connect your RealGeeks account in Pipedream.  
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add the server URL to your MCP-compatible app or chat client.  
4. Authenticate and select your RealGeeks client within the configuration flow.

## Pricing
Pricing details for the RealGeeks MCP Server are not provided in the available content. Refer to Pipedream or RealGeeks pricing documentation for up-to-date information.