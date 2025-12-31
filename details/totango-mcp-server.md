# Totango MCP Server

Customer Success Software MCP server that exposes Totango’s customer success platform via the Model Context Protocol (MCP), allowing AI agents to interact with customer health, success workflows, and lifecycle data.

## Overview
- **Type:** MCP server (Model Context Protocol)
- **Category:** Business & Commerce MCP Servers
- **Provider/Brand:** Totango (delivered via Pipedream Connect)
- **Primary Use Case:** Enable AI clients and chat-based tools to access and work with Totango customer success data and workflows.
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible endpoint**
  - Provides a static MCP server URL that works for all clients: `https://mcp.pipedream.net/v2`.
  - Designed to be added directly to MCP-compatible chat clients and AI tools.

- **Authentication at client setup**
  - Uses a single shared server URL; each user authenticates when adding the server to their application.
  - Keeps Totango-specific credentials out of the URL and tied to the client configuration instead.

- **Totango customer success integration (conceptual)**
  - Surfaces Totango’s customer success platform through MCP so AI agents can interact with:
    - Customer health data
    - Success workflows
    - Customer lifecycle information

- **Chat client integration guidance**
  - Support for adding the server to different chat clients (instructions available via the configuration page on Pipedream Connect).
  - Central configuration reference for setup, environment variables, and connection details.

- **Pipedream Connect infrastructure**
  - Hosted and operated via Pipedream Connect.
  - Benefits from Pipedream’s standard platform capabilities (e.g., managed hosting and configuration pages for MCP servers).

## Setup
- Use the static MCP server URL in your MCP-compatible client:
  - **Server URL:** `https://mcp.pipedream.net/v2`
- Complete authentication and configuration in your chosen chat or AI client following Pipedream’s configuration guidance.

## Pricing
- Not specified in the provided content.

## Links
- Source / App page: https://mcp.pipedream.com/app/totango
- Configuration & setup (via Pipedream Connect): https://pipedream.com/connect
- Terms: https://pipedream.com/terms
- Privacy Policy: https://pipedream.com/privacy