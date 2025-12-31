# Dripcel MCP Server

Automated SMS marketing integration for MCP workflows.

## Overview
Dripcel MCP Server is an MCP (Model Context Protocol) server integration that connects Dripcel’s automated SMS marketing capabilities into compatible chat or MCP-enabled applications. It is provided via a static MCP server URL hosted by Pipedream.

- **Type:** MCP server integration
- **Category:** Business & Commerce – MCP Servers
- **Primary Use Case:** Automated SMS marketing, campaigns, and marketing automation via MCP workflows

## Features
- **Automated SMS Marketing Integration**  
  - Exposes Dripcel’s SMS marketing capabilities through the MCP protocol.  
  - Designed for use inside MCP-compatible clients and workflows.

- **Static MCP Server URL**  
  - Single static endpoint for all clients:  
    `https://mcp.pipedream.net/v2`  
  - Authentication is performed when adding the server in the client, not by changing the URL.

- **MCP Client Compatibility**  
  - Can be added to various chat or MCP-enabled applications as an external MCP server.  
  - Configuration guidance is available through a general configuration page (per client instructions).

- **Hosted by Pipedream**  
  - MCP server infrastructure is provided and managed by Pipedream Connect.

## Setup & Usage
1. **Copy the MCP server URL**  
   Use `https://mcp.pipedream.net/v2` as the server endpoint in your MCP-compatible app.
2. **Add to your chat/MCP client**  
   - Open your client’s MCP or tools configuration.  
   - Add a new MCP server with the URL above.  
   - Authenticate when prompted by your client.
3. **Configure Workflows**  
   - Use the integrated MCP tools to trigger and manage automated SMS marketing actions from Dripcel (exact tools and actions depend on your client and Dripcel configuration).

## Pricing
The provided content does not list any pricing or plans for the Dripcel MCP Server or related services.