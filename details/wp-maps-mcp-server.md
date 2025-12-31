# WP Maps MCP Server

## Overview
WP Maps MCP Server is an MCP (Model Context Protocol) server that connects WP Maps (a WordPress maps and store locator solution) to MCP-compatible chat or AI clients. It enables interaction with WordPress-based map and store locator functionality through a standardized MCP endpoint.

- **Type:** MCP server / integration
- **Ecosystem:** WordPress, WP Maps, MCP-compatible clients
- **Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible endpoint**
  - Provides a static MCP server URL (`https://mcp.pipedream.net/v2`) usable across different clients.
  - Intended to be added as a server in any supported chat or AI client that implements MCP.

- **WP Maps integration**
  - Designed to work with the WP Maps plugin for WordPress.
  - Enables interaction with WordPress map and store locator features via MCP (as described in the item metadata):
    - Access and work with map data defined in WP Maps.
    - Surface store locator information managed in WordPress.

- **Client-agnostic setup**
  - Single static URL works for all clients; authentication is handled when configuring the server in each client.
  - Configuration guidance available via a generic “Configuration” page for adding the server to different chat clients.

- **Pipedream Connect backend**
  - Hosted and operated via Pipedream Connect infrastructure.

## Usage
1. Install and configure the WP Maps plugin on your WordPress site (outside this MCP server page).
2. In your MCP-compatible client, add a new MCP server using:
   - **Server URL:** `https://mcp.pipedream.net/v2`
3. Authenticate and complete client-specific configuration as directed by that client’s setup instructions.

## Pricing
The provided content does not list any pricing or plans for WP Maps MCP Server.