# ChuckNorris.io MCP Server

## Overview
ChuckNorris.io MCP Server is an MCP-compatible service that exposes the free ChuckNorris.io JSON API, allowing applications and chat clients to retrieve hand-curated Chuck Norris facts.

- **Type:** MCP Server / JSON API
- **Category:** Search & Discovery MCP Servers
- **Use case:** Entertainment, fun facts integration in MCP-compatible tools and chat clients
- **Base MCP URL:** `https://mcp.pipedream.net/v2`

## Features
- **Access to Chuck Norris facts**
  - Retrieves hand-curated Chuck Norris jokes and facts via JSON.
  - Suitable for embedding into MCP-enabled chat clients and tools.

- **MCP-compatible static endpoint**
  - Uses a single static MCP server URL: `https://mcp.pipedream.net/v2`.
  - Same URL works across all compatible clients.

- **Authentication at client setup**
  - Authentication is performed when adding the server to an application or client (details depend on client configuration).

- **Client-agnostic integration**
  - Designed to be added to multiple chat clients and MCP applications.
  - Configuration guidance available per client type (via the linked configuration page).

- **Hosted by Pipedream Connect**
  - Runs on Pipedream’s infrastructure, so users don’t need to self-host the MCP server.

## Pricing
- The underlying ChuckNorris.io API is described as a **free JSON API** for Chuck Norris facts.
- No additional pricing information is provided for the MCP server hosting itself.

## Technical Details
- **Protocol:** MCP (Model Context Protocol) server
- **Data format:** JSON responses
- **Endpoint:** `https://mcp.pipedream.net/v2` (static for all clients)

## Getting Started
1. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
2. Add it to your MCP-compatible chat client or application.
3. Authenticate during setup as required by your client.
4. Use available tools within the client to request Chuck Norris facts from the server.