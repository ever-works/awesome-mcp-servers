# Unisender MCP Server

UniSender MCP Server is an MCP integration that connects UniSender’s email marketing platform to MCP-compatible clients, enabling automated interactions with UniSender’s email marketing and subscriber management services.

## Overview
- **Type:** MCP server integration
- **Service:** UniSender (email marketing)
- **Category:** business & commerce – MCP servers
- **Use cases:** Automating email campaigns, managing subscribers, and integrating UniSender workflows into MCP-based applications.

## Features
- **MCP-based access to UniSender**
  - Exposes UniSender’s email marketing capabilities through the Model Context Protocol (MCP).
  - Designed to be used from any compatible chat or MCP client.

- **Static MCP server endpoint**
  - Single, static URL for all clients:
    - `https://mcp.pipedream.net/v2`
  - Same endpoint used across different chat or MCP applications.

- **Authentication at client setup**
  - Authentication is performed when adding the server to your application or chat client.
  - Supports secure access to UniSender resources through the MCP layer.

- **Client-agnostic integration**
  - Can be added to various chat clients that support MCP.
  - Configuration guidance is available via the generic configuration documentation (e.g., how to register the MCP server URL in your client).

- **Email marketing and automation use**
  - Built specifically for UniSender’s email marketing service.
  - Intended for tasks like automating campaigns and managing subscribers via MCP (exact tool list not detailed on the page).

## Configuration
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- Add this URL as an MCP server in your compatible application or chat client.
- Follow your client’s MCP configuration instructions to complete auth and start using UniSender via MCP.

## Pricing
The provided content does not list any pricing or plans for the Unisender MCP Server or UniSender service.