# Simplesat MCP Server

## Overview
Simplesat MCP Server is a Model Context Protocol (MCP) server integration that connects Simplesat’s customer feedback and survey data with AI/chat applications via a static MCP endpoint. It is provided through Pipedream and is intended for collecting and analyzing customer feedback survey data (e.g., CSAT) within compatible MCP clients.

- **Category:** Business & Commerce – MCP Servers  
- **Use Cases:** Customer feedback analysis, CSAT survey data access, integrating survey insights into AI workflows.

## Features
- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Designed to be added to any MCP-compatible chat or AI client.

- **Simplesat account connection**  
  - Connects to a Simplesat account to access survey data.  
  - Requires authenticating your Simplesat account when adding the server to your application.

- **Client selection workflow**  
  - After connecting your Simplesat account, you select the relevant client within Simplesat to start using the integration.

- **Tool-based interaction model**  
  - Exposes “available tools” (MCP actions) within supported clients for working with Simplesat data (the page shows these as dynamically loaded tools/actions).  
  - Intended for operations like collecting and analyzing customer feedback survey data via AI agents.

- **Central configuration resource**  
  - Provides a configuration flow within Pipedream.  
  - Links to a full configuration page for more detailed setup instructions.

## Configuration / Setup
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
- Add the server to your MCP-compatible app or chat client.  
- Authenticate with your Simplesat account when prompted.  
- Select the appropriate client in Simplesat to begin using the MCP tools.

## Pricing
- No pricing information is provided in the available content.