# LinearB MCP Server

**Category:** Development Tools / MCP Servers  
**Brand:** LinearB  
**Source:** https://mcp.pipedream.com/app/linearb

## Overview
The LinearB MCP Server connects MCP-compatible clients (such as ChatGPT) to the LinearB software delivery management platform. It is designed for engineering leaders and teams to work with incidents and delivery operations data directly from their chat or MCP-enabled environments.

## Features
- **MCP-compatible endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Works with multiple MCP clients (e.g., ChatGPT / OpenAI clients)

- **LinearB account integration**  
  - Connects to an existing LinearB account via Pipedream  
  - Supports authentication when adding the server to an MCP client  
  - Central configuration via the Pipedream configuration page

- **Incident management tools**  
  - **Search Incidents**  
    - Search for incidents within the LinearB platform  
    - Exposed as an MCP tool/action (`search-incidents`)  
    - Intended for querying and retrieving incident information
  - **Create Incident**  
    - Create new incidents in LinearB from an MCP client  
    - Exposed as an MCP tool/action (`create-incident`)  
    - Enables chat-based or automated incident creation workflows

- **Client integration guides**  
  - Specific guidance for connecting from ChatGPT (OpenAI)  
  - General documentation via the Pipedream MCP configuration page

## Use Cases
- Query existing incidents from LinearB directly in an MCP-aware chat client.
- Create new incidents from conversations or automated workflows without leaving the chat environment.
- Integrate incident workflows from LinearB into broader engineering operations automations.

## Pricing
The provided content does not specify any pricing or plans for the LinearB MCP Server. Refer to the source page or LinearB/Pipedream documentation for current pricing details.