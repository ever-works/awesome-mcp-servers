# Linkish MCP Server

All-in-one bookmarking manager MCP server for integrating Linkish’s link and bookmark management into MCP-compatible clients.

## Overview
- **Name:** Linkish MCP Server  
- **Category:** File Management MCP Servers  
- **Provider / Brand:** Linkish (via Pipedream Connect)  
- **Description:** MCP server that exposes Linkish’s bookmarking and link management capabilities to MCP tools and chat clients, enabling interaction with Linkish from within your applications.
- **Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible bookmarking backend**  
  - Provides an MCP server endpoint that tools and clients can connect to.
  - Designed to integrate Linkish’s all-in-one bookmarking and link management features into any MCP-enabled app.

- **Static server URL**  
  - Uses a single static URL (`https://mcp.pipedream.net/v2`) that works across supported clients.
  - No per-client URL needed; configuration is the same for all clients.

- **Client-agnostic integration**  
  - Can be added to multiple chat or MCP clients.  
  - Documentation references selecting your chat client and a general configuration page for setup.

- **Authentication at connection time**  
  - Authentication occurs when adding the server to the application, not via per-client URLs.

- **Hosted via Pipedream Connect**  
  - Infrastructure and serving handled by Pipedream’s Connect platform.

> Note: The content implies “all-in-one bookmarking manager” and “link management” capabilities, but does not enumerate specific bookmark operations. Those capabilities are exposed through the MCP tools once configured.

## Integration & Configuration
- Use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add this URL as a new MCP server in your chat client or MCP-enabled application.
- Follow client-specific instructions on the associated Configuration page (not included in the provided content).

## Pricing
- No pricing information is provided in the supplied content.