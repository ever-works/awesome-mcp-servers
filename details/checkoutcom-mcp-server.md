# Checkout.com MCP Server

An MCP server that exposes Checkout.com payment services and operations to power payment workflows via MCP-enabled clients.

## Overview
- **Type:** MCP server (tooling endpoint)
- **Category:** Business & Commerce / MCP Servers
- **Provider / Brand:** Checkout.com (via Pipedream Connect)
- **Purpose:** Enable applications and chat clients that support MCP to interact with Checkout.com payment services for building payment-related workflows.

## Features
- **MCP-compatible server:**
  - Exposes Checkout.com payment services and operations through the Model Context Protocol (MCP).
  - Designed to be used by any MCP-enabled client (e.g., compatible chat or agent tools).
- **Static server URL:**
  - Single, static endpoint for all clients: `https://mcp.pipedream.net/v2`.
  - Same URL works across different MCP clients.
- **Authentication handled at client setup:**
  - Authentication is performed when adding the server to your application or client configuration.
- **Client-agnostic integration:**
  - Can be added to various chat clients that support MCP to power payment workflows within conversational interfaces.
- **Configuration documentation:**
  - Dedicated configuration guidance available via a “Configuration” page (for setup and usage details).

## Usage
- Add the MCP server URL `https://mcp.pipedream.net/v2` to your MCP-enabled app or chat client.
- Configure authentication and options following the client’s or configuration page instructions.

## Pricing
- No pricing information is provided in the available content.