# BlueSnap MCP Server

Global payment processing platform integration via the Model Context Protocol (MCP), provided by Pipedream.

## Overview
- Integrates BlueSnap’s global payment processing and billing capabilities into MCP-compatible clients.
- Exposed via a single static MCP server URL usable by any supported chat or MCP client.

## Features
- **Static MCP Endpoint**: Use a single, fixed MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
- **Client-Agnostic Integration**: The same MCP server URL works across different MCP-compatible chat clients and tools.
- **Authentication at Client Setup**: Authentication is handled when adding the server to your specific application or client, rather than via different URLs.
- **Pipedream-hosted Infrastructure**: Operated and maintained by Pipedream (via Pipedream Connect), avoiding custom hosting of the MCP server.
- **Configuration Documentation**: Full configuration guidance available via a dedicated configuration page (for connecting the MCP server to various clients).

## Use Cases
- Integrate BlueSnap payment and billing workflows into MCP-enabled AI assistants or chat applications.
- Standardize access to BlueSnap’s global payment processing through a single MCP server endpoint.

## Access & Configuration
- **MCP Server URL**: `https://mcp.pipedream.net/v2`
- Add this URL as an MCP server in your compatible client, then follow that client’s authentication and configuration flow.

## Pricing
- Not specified in the provided content.