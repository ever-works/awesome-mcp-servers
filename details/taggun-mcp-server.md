# Taggun MCP Server

An MCP server that exposes Taggun’s real-time receipt OCR APIs to MCP-compatible clients.

## Overview

- **Type:** MCP server (for Model Context Protocol clients)
- **Purpose:** Real-time OCR of receipts via Taggun’s developer-focused APIs
- **Provider / Host:** Pipedream Connect
- **Category:** Content extraction & summarization – MCP servers
- **Slug:** `taggun-mcp-server`

## Features

- **Real-time receipt OCR**
  - Extracts data from receipt images using Taggun’s OCR capabilities.
  - Designed for developer integration via MCP-compatible tools.

- **MCP server endpoint**
  - Single static MCP server URL for all clients:  
    `https://mcp.pipedream.net/v2`
  - URL is client-agnostic and reused across different MCP chat clients.

- **Authentication at client setup**
  - Authentication is handled when adding the server to the client application (credentials / keys not detailed here).

- **Multi-client compatibility**
  - Intended for use with multiple MCP chat clients; users add the server to their preferred client.

- **Configuration documentation**
  - Additional setup and configuration details available via a dedicated Configuration page (linked from the source site).

## Integration

- **Add to your app**
  - Select your MCP-compatible chat client and configure it using the static server URL.
  - Follow the client-specific instructions from the configuration documentation.

## Pricing

- Not specified in the provided content.

## Links

- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Pipedream Connect:** https://pipedream.com/connect
- **Configuration page:** Linked as “Configuration” on the source site
- **Terms:** https://pipedream.com/terms
- **Privacy Policy:** https://pipedream.com/privacy