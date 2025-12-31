# ecwid MCP Server

Online store platform MCP Server integration for Ecwid that allows MCP-based tools to interface with Ecwid’s ecommerce data and operations.

## Overview
The **ecwid MCP Server** is an MCP Server integration, powered by Pipedream Connect, that exposes Ecwid’s online store platform to MCP-compatible clients. It enables chat clients and other MCP-based tools to connect to an Ecwid store and work with ecommerce data and workflows.

- **Type:** MCP Server integration
- **Category:** Business & Commerce – MCP Servers
- **Platform:** Ecwid online store
- **Provider:** Pipedream
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

- **MCP-based integration**
  - Implements an MCP Server endpoint that MCP-compatible tools and chat clients can use.
  - Uses a single static base URL for all clients.

- **Ecwid online store connectivity**
  - Connects MCP tools to Ecwid’s ecommerce platform.
  - Designed for managing ecommerce data and operations (e.g., store data, orders, online-store resources) via MCP.

- **Static server URL**
  - Shared, static MCP server URL: `https://mcp.pipedream.net/v2`.
  - Works for every client; authentication is handled when adding the server to the application.

- **Client-agnostic usage**
  - Can be added to multiple MCP-compatible chat clients.
  - Supports configuration through client-specific instructions or via a central configuration page.

- **Configuration documentation**
  - Setup and configuration steps are available via a dedicated configuration page (linked from the product page).

## Authentication

- Authentication is performed when adding the MCP server to your application or chat client.
- The same static URL is used for all clients; credentials or tokens are tied to the client configuration rather than the URL itself.

## Technical Details

- **MCP Server Endpoint:** `https://mcp.pipedream.net/v2`
- **Transport / Access:** HTTPS endpoint suitable for MCP-compatible tools.
- **Integration Layer:** Powered by Pipedream Connect.

## Pricing

The provided content does not list any pricing or plan information for the ecwid MCP Server integration.