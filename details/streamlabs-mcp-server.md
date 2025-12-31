# Streamlabs MCP Server

## Overview
Streamlabs MCP Server exposes Streamlabs live streaming software functionality via the Model Context Protocol (MCP), enabling automation and tooling around streaming workflows through compatible MCP clients.

- **Type:** MCP server / integration
- **Category:** Media processing, live streaming automation
- **Provider / Platform:** Pipedream Connect
- **URL (MCP endpoint):** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server** exposing Streamlabs-related capabilities via the Model Context Protocol for use by MCP-aware tools and chat clients.
- **Static server URL** (`https://mcp.pipedream.net/v2`) that works across all supported MCP clients.
- **Client-agnostic integration**: intended to be added to various chat clients or MCP-compatible applications for streaming-related workflows.
- **Authentication at configuration time**: authentication is performed when you add the MCP server to your application/client.
- **Configuration guidance**: documentation available via a configuration page describing how to add the server to different clients (e.g., chat clients).

## Usage
1. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
2. Add this URL as an MCP server in your MCP-compatible application or chat client.
3. Authenticate when prompted during server setup.
4. Use your client’s interface to access Streamlabs-related streaming functionality exposed by the MCP server.

## Pricing
- Described as **“Free live streaming software”**; no specific paid plans or pricing tiers are listed in the provided content.