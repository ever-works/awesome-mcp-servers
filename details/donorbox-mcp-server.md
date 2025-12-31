# Donorbox MCP Server

Nonprofit fundraising software MCP server integration for Donorbox, enabling MCP-compatible tools and chat clients to work with nonprofit fundraising data and donation workflows.

## Overview
- **Type:** MCP server (Model Context Protocol server)
- **Category:** Business & Commerce – MCP Servers
- **Use case:** Allow chat clients and MCP tools to access and interact with Donorbox-based nonprofit fundraising and donation workflows via a standardized server endpoint.

## Features
- **Standard MCP endpoint**  
  - Provides a static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL is used for all clients.

- **Client-agnostic integration**  
  - Designed to be added to compatible chat clients and MCP-aware applications.  
  - Works with multiple clients; configuration is handled on the client side.

- **Authentication at connection time**  
  - Authentication occurs when adding the server to your application or client (exact method depends on the client / app configuration).

- **Configuration documentation**  
  - Full configuration guidance available via a dedicated configuration page (linked from the product page).

- **Pipedream Connect integration**  
  - MCP server is powered and hosted via Pipedream Connect infrastructure.

## Technical Details
- **MCP server URL:** `https://mcp.pipedream.net/v2`  
- **Integration pattern:** Add this URL as an MCP server in your chosen chat client, then authenticate and configure according to the client’s instructions.

## Pricing
- Not specified in the provided content.