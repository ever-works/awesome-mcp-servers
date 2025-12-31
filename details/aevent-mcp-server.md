# AEvent MCP Server

## Overview
AEvent MCP Server is a Model Context Protocol (MCP) server that connects AEvent’s webinar automation and scheduling capabilities—integrated with Zoom and GoToWebinar—to MCP-driven workflows. It is provided and hosted by Pipedream.

- **Type:** MCP server (integration/service)
- **Category:** Business & Commerce – MCP Servers
- **Integrations:** AEvent, Zoom, GoToWebinar
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server**
  - Exposes AEvent functionality through the Model Context Protocol.
  - Can be added to any MCP-enabled client via a single static URL.

- **Static server endpoint**
  - Uses one shared endpoint for all clients: `https://mcp.pipedream.net/v2`.
  - Authentication occurs when you add the server to your application, not via different URLs.

- **Webinar platform integration**
  - Connects to AEvent’s webinar automation and scheduling capabilities.
  - Designed to work with AEvent’s integrations with:
    - Zoom
    - GoToWebinar

- **Workflow automation support**
  - Enables MCP-driven workflows that can interact with AEvent’s webinar tools (e.g., automated scheduling, show-up optimization, and related webinar operations handled by AEvent).

- **Client-agnostic usage**
  - Can be added to multiple MCP-compatible chat or AI clients.
  - Configuration guided via a generic “add the server to your app” flow and a central configuration page.

## Setup & Configuration
- **Server URL to use in clients**: `https://mcp.pipedream.net/v2`
- **Authentication**: Performed when adding the server within your MCP client’s configuration (exact method depends on the client).
- Additional setup details are referenced via a configuration page (not included here).

## Provider
- **Brand:** Pipedream
- **Product name:** AEvent MCP Server

## Pricing
- Not specified in the provided content. No pricing or plan details are available from this source.