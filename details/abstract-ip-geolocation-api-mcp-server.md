# Abstract - IP Geolocation API MCP Server

## Overview
The **Abstract - IP Geolocation API MCP Server** exposes Abstract’s IP Geolocation API as an MCP-compatible server, enabling IP-based location lookups to be integrated into MCP clients and workflows. It is hosted and configured via Pipedream’s MCP infrastructure.

## Features
- **MCP-compatible server**: Provides a static MCP server endpoint that can be added to any compatible MCP client.
- **Static server URL**: Uses a single, fixed MCP server URL for configuration:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic integration**: The same MCP server URL works for all supported chat or MCP clients; authentication is handled when adding the server to the application.
- **ChatGPT (OpenAI) integration guidance**: Includes setup instructions specific to ChatGPT (OpenAI) as an MCP client, with a link to a detailed configuration guide.
- **Central configuration page**: A dedicated configuration page on Pipedream for viewing and managing MCP server setup details.
- **Account-based connection**: Requires signing in to Pipedream to connect your Abstract IP Geolocation API account and manage associated configurations.
- **Pipedream-hosted**: Runs on Pipedream’s “Connect” infrastructure for MCP servers.
- **Tooling placeholder**: Currently shows no concrete tools exposed in the UI yet (indicates that tools/endpoints may be added or expanded in the future).

## Usage
1. Sign in to Pipedream to connect your Abstract IP Geolocation API account.
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
3. Add this URL as an MCP server in your MCP-compatible client (e.g., ChatGPT via the provided guide).
4. Authenticate when prompted by your client or Pipedream during server addition.

## Pricing
- No specific pricing information is provided in the available content for this MCP server or its usage.