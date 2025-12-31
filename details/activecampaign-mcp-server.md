# ActiveCampaign MCP Server

## Overview
The ActiveCampaign MCP Server exposes ActiveCampaign’s email marketing, marketing automation, and CRM capabilities as MCP-accessible tools within the Pipedream ecosystem. It allows applications and chat clients that support MCP to interact with ActiveCampaign through a standardized server endpoint.

- **Category:** Business & Commerce – MCP Servers  
- **Brand:** ActiveCampaign  
- **Integration Host:** Pipedream  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL (`https://mcp.pipedream.net/v2`) that works for all clients.  
  - Designed to be added to MCP-capable applications and chat clients.

- **Authentication at client setup**  
  - Authentication occurs when adding the server to your application or client, rather than per-URL change.

- **ActiveCampaign capability exposure**  
  - Surfaces ActiveCampaign’s core domains as MCP tools:  
    - Email marketing functions  
    - Marketing automation functions  
    - CRM-related functions
  - Tools are dynamically loaded within Pipedream (“Available tools / Loading actions / Loading available tools…”), indicating multiple MCP-accessible actions and events mapped to ActiveCampaign.

- **Client integration guidance**  
  - Workflow for setup:  
    1. Connect your ActiveCampaign account in Pipedream.  
    2. Copy the static MCP server URL.  
    3. Add the server to your chosen chat client or MCP-enabled app.  
  - Option to view a full configuration page (outside the provided content) for more detailed setup steps.

## Configuration
- **Connect ActiveCampaign account** within Pipedream before using MCP tools.  
- **Use a single static URL** for all MCP clients, simplifying configuration.  
- **Add server to supported chat clients or applications** that can consume MCP servers.

## Pricing
The provided content does not include any pricing or plan details for the ActiveCampaign MCP Server or related services.