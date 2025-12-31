# Mapbox MCP Server

Mapbox MCP Server is an MCP (Model Context Protocol) server that exposes Mapbox navigation, mapping, and location services to compatible clients.

## Overview
- **Name:** Mapbox MCP Server  
- **Category:** Data Access / Integration / MCP Servers  
- **Provider / Brand:** Mapbox (via Pipedream Connect)  
- **Purpose:** Enable MCP-compatible applications to access Mapbox navigation, mapping, and location-intelligence capabilities for people, packages, and vehicles.

## MCP Server Endpoint
- **MCP Server URL (static):** `https://mcp.pipedream.net/v2`  
  - Same URL for all supported MCP clients.  
  - Authentication is handled when adding/configuring the server in the client application.

## Features
- **MCP Integration Endpoint**  
  - Single static MCP server URL usable across different MCP clients.  
  - Designed to be added as an external tool/server in MCP-compatible chat or agent applications.

- **Access to Mapbox Services (via MCP)**  
  - Provides programmatic access to Mapbox’s navigation, mapping, and location services through MCP.  
  - Intended for use cases involving routing and navigation for people, packages, and vehicles.  
  - Supports location-intelligence workflows within chat or agent environments (e.g., maps, routes, positioning), subject to client configuration and Mapbox/Pipedream capabilities.

- **Client-Agnostic Configuration**  
  - Works with multiple chat or agent clients that support MCP.  
  - Configuration instructions are available per client type (via the referenced configuration page).  
  - Central configuration page for complete setup details.

- **Pipedream Connect Integration**  
  - Operated and hosted via Pipedream Connect.  
  - Governed by Pipedream’s Terms and Privacy Policy.

## Setup & Configuration
- Use the static URL `https://mcp.pipedream.net/v2` when adding the Mapbox MCP Server to your MCP-capable app.  
- Complete authentication and any required credentials during server addition in the client.  
- Refer to the provider’s configuration page for client-specific setup steps.

## Pricing
- Not specified in the provided content.