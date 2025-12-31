# Whautomate MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Whautomate  
**Slug:** whautomate-mcp-server

## Description
Whautomate MCP Server is an MCP server integration for the Whautomate omnichannel customer engagement platform. It exposes Whautomate’s messaging and engagement capabilities (including WhatsApp and other channels) through the Model Context Protocol (MCP), allowing compatible applications and chat clients to interact with Whautomate via a unified MCP endpoint.

## Features
- **MCP-based access to Whautomate**: Provides an MCP server interface to Whautomate’s omnichannel customer engagement platform.
- **Omnichannel messaging**: Designed to work with multiple messaging channels, including WhatsApp and other supported messaging platforms (as provided by Whautomate).
- **Static server endpoint**: Uses a single static MCP server URL for all clients:
  - `https://mcp.pipedream.net/v2`
- **Per-client authentication**: Authentication is handled when adding the server to your application or client, allowing the same URL to be used across different accounts.
- **Chat client integration**: Can be added to compatible chat clients; configuration guidance is available per client via the configuration page.
- **Pipedream-hosted**: The MCP server is hosted through Pipedream’s infrastructure.

## Configuration
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-compatible application or chat client.
- Authenticate your Whautomate account when prompted by the client.
- Additional configuration details are available on the referenced configuration page (not included in the provided content).

## Pricing
- Not specified in the provided content.