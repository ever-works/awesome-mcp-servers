# Airbyte MCP Server

## Overview
Airbyte MCP Server exposes Airbyte’s ELT data connectors via the MCP protocol, allowing you to move data between databases, APIs, and data warehouses from compatible MCP-enabled clients (such as chat-based tools). It is provided and hosted through Pipedream.

- **Category:** Data access & integration (MCP servers)
- **Provider/Brand:** Airbyte (via Pipedream)
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-based access to Airbyte**  
  - Static MCP server URL that works across supported MCP clients.  
  - Authentication handled when adding the server to your application.

- **ELT data connectors**  
  - Uses Airbyte’s community of ELT data connectors to move data between:  
    - Databases  
    - APIs  
    - Data warehouses

- **Workspace management tools (actions)**  
  The MCP server currently exposes 4 workspace-related actions as tools:
  1. **Create Workspace** – Create a new workspace in Airbyte.  
  2. **List Workspaces** – List existing workspaces in Airbyte.  
  3. **Update Workspace** – Update properties of an existing Airbyte workspace.  
  4. **Delete Workspace** – Delete an existing Airbyte workspace.

- **Client integration**  
  - Can be added to MCP-compatible chat clients (e.g., ChatGPT via OpenAI).  
  - Step-by-step configuration available via the Pipedream configuration guide (external link).

- **Hosted by Pipedream**  
  - MCP server operated through Pipedream Connect infrastructure.

## Setup
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- Add this URL in your MCP-compatible client configuration, then authenticate your Airbyte account when prompted.

## Pricing
The provided content does not include any pricing information or plan details for the Airbyte MCP Server or its usage via Pipedream.