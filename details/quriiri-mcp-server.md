# Quriiri MCP Server

**Category:** Messaging MCP Servers  
**Tags:** messaging, customer-engagement, campaigns

## Overview
Quriiri MCP Server is an MCP (Model Context Protocol) server integration that exposes Quriiri’s customer communication and messaging platform capabilities to MCP-compatible clients. It allows applications and chat clients to interact with Quriiri via a standardized MCP endpoint.

## MCP Endpoint
- **Server URL (static for all clients):** `https://mcp.pipedream.net/v2`
- Authentication is performed when adding the server to a client/application.

## Features
- **MCP Integration for Quriiri**
  - Provides an MCP-compatible server that connects client applications to Quriiri’s messaging platform.
  - Accessible via a single static URL that can be reused across different MCP clients.
- **Customer Communication Platform Access**
  - Interfaces with Quriiri, a domestic communication platform focused on customer messaging and engagement.
  - Designed to support customer communication scenarios such as messaging and campaigns (as indicated by the item tags).
- **Client-Agnostic Setup**
  - Same server URL for all supported MCP clients.
  - Configuration handled at the client side by adding the MCP server URL and authenticating.

## Configuration
- Add the MCP server by using the static URL: `https://mcp.pipedream.net/v2`.
- Follow your specific MCP/chat client’s instructions to:
  - Register a new MCP server.
  - Provide the server URL.
  - Complete authentication.
- A general configuration reference is available via the provider’s configuration documentation (link referenced in the source content).

## Pricing
- No pricing information is provided in the available content.