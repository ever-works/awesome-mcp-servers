# Power Automate MCP Server

**Category:** Workflow Automation MCP Servers  
**Brand:** Microsoft Power Automate  
**Source:** https://mcp.pipedream.com/app/power_automate

## Overview
The Power Automate MCP Server is an MCP-compatible server that exposes Microsoft Power Automate’s low-code, AI-powered cloud automation capabilities as tools within MCP-enabled clients. It allows users to connect their Power Automate account and run automation flows and connectors directly from compatible chat or MCP applications.

## Features
- **MCP-compatible server endpoint**  
  - Static server URL for all clients: `https://mcp.pipedream.net/v2`  
  - Can be added to any MCP-capable application as a server.

- **Power Automate integration**  
  - Connects to a Microsoft Power Automate account.  
  - Enables triggering and managing cloud automation flows from MCP tools.  
  - Provides access to Power Automate’s low-code, AI-assisted automation features.

- **Client-agnostic configuration**  
  - Single URL works across different chat clients or MCP applications.  
  - Authentication occurs when adding the server in the client, not per-URL.

- **Tools exposure**  
  - Dynamically loads and exposes available Power Automate actions/tools to the MCP client (listed as “Available tools” once loaded).  
  - Designed to integrate Power Automate connectors and flows as callable MCP tools.

- **Cloud-based operation**  
  - Runs as a cloud-hosted MCP server managed by Pipedream.  
  - No local server setup required; configuration is done via the provided URL.

## Configuration
- Copy the static MCP server URL: `https://mcp.pipedream.net/v2`.  
- Add this URL as an MCP server in your chat client or MCP-enabled application.  
- Authenticate your Power Automate account when prompted in the client.  
- Once configured, available tools/actions will be loaded in the client.

## Pricing
The provided content does not include any pricing information for the Power Automate MCP Server.