# Melo MCP Server

An MCP Server integration for Melo that exposes Melo’s real estate API as MCP tools, enabling property data access directly from compatible MCP-enabled applications.

## Overview
- **Type:** MCP Server integration
- **Category:** Business & Commerce – MCP Servers
- **Provider / Brand:** Melo (via Pipedream)
- **Primary function:** MCP-based access to Melo’s comprehensive property data API
- **Static MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP server integration for Melo**  
  - Wraps Melo’s real estate API as an MCP-compliant server.  
  - Allows MCP-compatible clients (e.g., chat-based tools) to call Melo’s API via MCP tools.

- **Access to comprehensive property data**  
  - Designed to deliver property-related data via Melo’s “reactive” real estate API.  
  - Suitable for applications that need programmatic property information within an MCP environment.

- **Static server endpoint**  
  - Single static URL (`https://mcp.pipedream.net/v2`) used for all clients.  
  - Authentication handled when adding/configuring the server in your application.

- **Client-agnostic setup**  
  - Can be added to any MCP-compatible chat client or application.  
  - Documentation and setup details available through a configuration page on Pipedream.

- **Tool exposure within clients**  
  - Once configured, the server exposes “Available tools” (MCP actions) corresponding to Melo API operations.  
  - Tools are discoverable and load dynamically within the client interface.

## Configuration & Usage
- Configure Melo via the Pipedream interface and connect your Melo account.  
- Copy the static MCP server URL and register it in your MCP-enabled app.  
- Authenticate when prompted by your client/application during server setup.  
- After setup, use the exposed MCP tools to query or work with property data.

## Pricing
- No pricing information is provided in the available content. Refer to Melo or Pipedream’s official pages for current pricing and plan details.