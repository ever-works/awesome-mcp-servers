# noCRM.io MCP Server

Lead Management Software

## Overview
The noCRM.io MCP Server is an integration endpoint, powered by Pipedream Connect, that allows MCP-compatible chat clients or applications to connect to the noCRM.io lead management platform for working with leads and deals.

## MCP Server URL
- Base MCP server URL (static for all clients):
  - `https://mcp.pipedream.net/v2`
- Authentication is performed when adding the server to your application.

## Features
- **MCP-compatible server endpoint**
  - Provides a single static URL that can be used by any supported MCP client.
  - Uses authentication during client/server configuration rather than per-URL customization.
- **noCRM.io integration**
  - Connects MCP-based chat or automation clients to the noCRM.io lead management platform (focused on tracking and closing deals).
- **Client-agnostic setup**
  - Designed to be added from various chat clients that support MCP servers.
- **Centralized configuration**
  - Configuration details and setup steps are documented on a dedicated configuration page (external to this summary).

## Setup
- Use the static MCP server URL `https://mcp.pipedream.net/v2` when adding a new MCP server in your client.
- Complete authentication within your client’s MCP configuration flow.
- Refer to the platform’s configuration page for client-specific instructions.

## Pricing
- Not specified in the provided content.