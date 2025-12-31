# BigCommerce MCP Server

## Overview
The BigCommerce MCP Server is an integration that exposes BigCommerce ecommerce store data and operations via the Model Context Protocol (MCP). It allows applications (such as MCP-enabled chat or AI clients) to programmatically interact with modern BigCommerce stores through a standardized MCP server endpoint.

- **Category:** Business / Commerce MCP Server
- **Provider / Platform:** Pipedream
- **Ecommerce Platform:** BigCommerce
- **Protocol:** Model Context Protocol (MCP)
- **Static MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compliant server for BigCommerce**  
  - Provides a Model Context Protocol server that interfaces with BigCommerce ecommerce data and operations.
- **Programmatic access to ecommerce store data**  
  - Designed to give applications structured access to BigCommerce store information (e.g., catalog, orders, and related ecommerce entities) via MCP.
- **Programmatic operations on store resources**  
  - Intended to support actions/operations on a BigCommerce store (such as managing store entities) through MCP tools exposed by the server.
- **Static server endpoint**  
  - Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) that works for all clients.
- **Authentication at client configuration time**  
  - Authentication is handled when adding/configuring the MCP server in your application rather than requiring a per-client URL.
- **Client-agnostic integration**  
  - Can be used from any MCP-compatible chat or AI client; configuration is performed within the client using the provided server URL.

## Configuration & Usage
- Connect your BigCommerce account within the Pipedream-hosted interface.
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add this server URL to your MCP-compatible app or chat client and complete authentication.
- Once connected, the client can load available MCP tools/actions exposed for BigCommerce.

## Tags
- E-commerce  
- Online store  
- Orders

## Pricing
No pricing information is provided in the available content.