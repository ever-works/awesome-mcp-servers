# PingBell MCP Server

Instant notification server for website and app conversions, powered by Pipedream Connect.

## Overview
PingBell MCP Server is a Model Context Protocol (MCP) server that connects your application to PingBell so your team receives instant notifications whenever a conversion occurs on your website or app.

- **Type:** MCP server (workflow automation)
- **Purpose:** Send real-time team notifications on conversion events
- **Endpoint:** Shared static MCP server URL for all clients

## Features
- **Real-time conversion alerts**: Instantly notifies your team each time a conversion happens on your website or app.
- **Static MCP server URL**: Uses a single static server URL (`https://mcp.pipedream.net/v2`) that works for every compatible MCP client.
- **Per-client authentication**: Authentication is handled when adding the server to each application/client, not via different URLs.
- **Multi-client support**: Can be added to different chat or MCP-compatible clients to receive notifications where your team already works.
- **Configuration guidance**: Setup instructions available via a configuration page for adding the server to supported clients.
- **Pipedream Connect integration**: Runs on Pipedream Connect infrastructure for MCP servers.

## Technical Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Integration model:** Connects PingBell events (conversions) to MCP-compatible clients for notification delivery.

## Pricing
No pricing information is provided in the available content.