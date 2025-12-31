# 15Five MCP Server

## Overview
The 15Five MCP Server is an integration endpoint that connects the 15Five human-centered performance management platform to MCP-compatible chat or AI applications via Pipedream. It allows applications to interact with 15Five through a standardized MCP server URL.

- **Product type:** MCP server integration
- **Platform:** Pipedream
- **Category:** Human Resources / Performance Management

## Features
- **Standard MCP server endpoint**  
  - Uses a single static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL works for all 15Five clients; authentication is handled when adding the server to the application.

- **15Five platform integration**  
  - Connects to 15Five, a human-centered performance management platform for managers, employees, and organizations.  
  - Designed to support workflows around performance management and employee engagement (specific tools/actions are loaded dynamically within Pipedream).

- **Account configuration flow**  
  - “Configure 15Five” step to connect a 15Five account through Pipedream.  
  - Client selection after account connection.  
  - Status indication such as “Checking your account…” during setup.

- **MCP client compatibility**  
  - Can be added as an MCP server to various chat or AI clients.  
  - Client-specific setup instructions are provided within the Pipedream interface (select your chat client to learn how to get started).  
  - Full technical and configuration details are available via a dedicated configuration page on Pipedream.

- **Tool/action discovery**  
  - Tools and actions exposed by the 15Five integration are loaded dynamically (“Loading actions…”, “Loading available tools…”), enabling applications to access 15Five-related capabilities through the MCP interface.

## Setup
1. Connect your 15Five account in Pipedream.  
2. Select the appropriate client within Pipedream.  
3. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
4. Add the server URL to your MCP-compatible chat or AI application and complete authentication.

## Pricing
The provided content does not list any pricing or plan details for the 15Five MCP Server integration.