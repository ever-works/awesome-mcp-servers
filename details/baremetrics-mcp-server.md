# Baremetrics MCP Server

**Category:** Finance & Market Data MCP Servers  
**Tags:** analytics, SaaS, subscriptions

## Overview
Baremetrics MCP Server is a Model Context Protocol (MCP) server that exposes Baremetrics subscription analytics and SaaS metrics data to MCP-compatible clients. It is provided via Pipedream Connect using a single static endpoint that can be used across different MCP clients.

## MCP Endpoint
- **Server URL:** `https://mcp.pipedream.net/v2`  
  - Static URL used by all supported MCP clients
  - Authentication is performed when adding the server to an application

## Features
- **Baremetrics data access via MCP**
  - Provides MCP clients with access to Baremetrics subscription analytics
  - Supports retrieval and use of SaaS metrics data (e.g., subscription-related metrics) through MCP tools
- **Standardized MCP server endpoint**
  - Single, static MCP server URL for all clients
  - Centralized configuration through the same base endpoint used by other Pipedream MCP servers
- **Client-agnostic integration**
  - Designed to work with multiple MCP-compatible chat or AI clients
  - Configuration instructions available per client via the linked configuration page
- **Pipedream Connect integration**
  - Hosted and operated by Pipedream
  - Integrates with the broader Pipedream Connect ecosystem for MCP servers

## Usage
- Add the MCP server URL `https://mcp.pipedream.net/v2` to a supported MCP client.
- Authenticate with your Baremetrics / Pipedream account during setup in the client.
- Use the tools exposed by the server to query or work with Baremetrics subscription analytics and SaaS metrics.

## Pricing
- No pricing information is provided in the available content.