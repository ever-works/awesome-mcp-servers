# Celonis EMS MCP Server

**Category:** Data Analysis & Exploration MCP Servers  
**Brand:** Celonis  
**Source:** https://mcp.pipedream.com/app/celonis_ems

## Overview
The Celonis EMS MCP Server exposes the Celonis Execution Management System to AI agents and MCP-compatible applications. It allows agents to interact with process mining and execution data from Celonis EMS through a standardized MCP server endpoint.

## Features
- **MCP-compatible server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Can be added to any MCP-capable chat or agent client.

- **Celonis EMS integration**  
  - Connects to a Celonis EMS account and client.  
  - Enables access to process mining and execution management data (via EMS) for AI agents.

- **Account-based configuration**  
  - Requires connecting a Celonis EMS account.  
  - Client selection step after account connection.

- **Auth handled at application level**  
  - The same static URL is used for all clients; authentication is performed when adding the server to your application.

- **Tool exposure for agents**  
  - Designed to load and expose Celonis-related MCP tools / actions (listed dynamically as “Available tools”).

- **Multi-client usage**  
  - Can be added to different chat or agent clients; configuration guidance is provided per client type via the app’s UI.

## Configuration
- Connect a Celonis EMS account.  
- Select the desired Celonis client within your account.  
- Copy and use the MCP server URL: `https://mcp.pipedream.net/v2` when adding the server to your MCP-compatible application.

## Pricing
The provided content does not list any pricing or plans for the Celonis EMS MCP Server.