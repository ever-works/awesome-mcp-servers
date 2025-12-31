# Google Fit MCP Server

## Overview
The Google Fit MCP Server is an MCP (Model Context Protocol) server that connects MCP-compatible agents to Google Fit. It enables access to health and activity data so agents can perform fitness-related analysis and provide coaching or recommendations based on a user’s historical data.

- **Type:** MCP server / data-access integration
- **Category:** Health & activity data integration
- **Provider/Brand:** Google (via Pipedream Connect)
- **MCP Endpoint URL:** `https://mcp.pipedream.net/v2`

## Features
- **Google Fit data access**
  - Connects MCP agents to Google Fit health and activity data.
  - Supports using historical data for fitness analysis and coaching workflows.

- **Static MCP server URL**
  - Single static endpoint: `https://mcp.pipedream.net/v2`.
  - Same URL works across all compatible MCP clients.

- **Per-client authentication**
  - Authentication is performed when adding the server to each application or chat client.

- **Client-agnostic integration**
  - Can be added to multiple MCP-enabled chat clients.
  - Configuration guidance available via a central configuration page.

- **Pipedream Connect integration**
  - Operates via Pipedream Connect infrastructure.

## Usage
- Add MCP server URL to your MCP-compatible chat client or application.
- Authenticate when prompted to allow access to Google Fit data.
- Use the connected agent for fitness coaching and analysis based on your Google Fit history.

## Pricing
- Not specified in the provided content.

## Links
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Configuration Guide:** /configuration (from the source site)
- **Pipedream Connect:** https://pipedream.com/connect
- **Terms:** https://pipedream.com/terms
- **Privacy Policy:** https://pipedream.com/privacy