# Aylien News API MCP Server

## Overview
The Aylien News API MCP Server is an MCP-compatible integration that provides real-time access to enriched, tagged, and structured news feeds via the Aylien News API. It is delivered through Pipedream’s MCP infrastructure and can be added to compatible chat or MCP client applications.

- **Category:** Web Search MCP Servers
- **Use cases:** News-driven applications, content discovery, data analytics, model enrichment, real-time information retrieval

## Features
- **Real-time news access**
  - Access up-to-date news data streams via the Aylien News API.

- **Enriched and structured news data**
  - Provides news content that is enriched, tagged, and structured for easier downstream processing and analysis.

- **MCP-compatible server**
  - Exposes the Aylien News API as an MCP Server for integration with MCP-capable tools and chat clients.

- **Static MCP server endpoint**
  - Single static server URL for all clients:
    - `https://mcp.pipedream.net/v2`

- **Client-agnostic configuration**
  - The same MCP endpoint can be used across different MCP-compatible clients; authentication is handled when you add the server to your application.

- **Account-based configuration**
  - Requires connecting an Aylien account within Pipedream before use.

- **Tool discovery within MCP**
  - Once added, the server exposes available tools/actions (e.g., for querying news) that can be discovered and invoked from your MCP client.

## Configuration & Integration
- Connect your Aylien News API account in Pipedream.
- Use the MCP server URL `https://mcp.pipedream.net/v2` when adding the server to your MCP-compatible app or chat client.
- Follow client-specific instructions (within your MCP/chat client) to complete setup.

## Pricing
Pricing details are not provided in the available content. Refer to Pipedream and Aylien documentation or dashboards for current pricing and plan information.