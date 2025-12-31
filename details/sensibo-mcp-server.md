# Sensibo MCP Server

Smart air conditioner integration via Model Context Protocol (MCP).

## Overview

Sensibo MCP Server is a Model Context Protocol server that connects AI systems to Sensibo’s smart air conditioning devices. It enables intelligent control and monitoring of climate devices through MCP tools, allowing applications and chat-based clients to interact programmatically with Sensibo-powered air conditioners.

- **Type:** MCP server (Model Context Protocol)
- **Category:** Home automation / smart-home device control
- **Brand:** Sensibo
- **Slug:** `sensibo-mcp-server`
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

- **MCP-compatible endpoint**
  - Provides a static MCP server URL (`https://mcp.pipedream.net/v2`) that works across MCP-compatible clients.
  - Designed to be added as a server within MCP-aware chat and AI applications.

- **Sensibo smart AC integration**
  - Connects AI systems to Sensibo smart air conditioning devices.
  - Enables intelligent control and monitoring of climate devices via MCP tools (e.g., turning devices on/off, adjusting settings, querying status – as supported by the Sensibo integration in the MCP backend).

- **Authentication at client setup**
  - Uses a common, static server URL; authentication is performed when the server is added to an application or chat client.

- **Multi-client compatibility**
  - Intended to be used from various MCP-capable chat clients and applications.
  - Configuration details and client-specific setup are available through the linked configuration resources (not specific in the provided content).

## Pricing

- Not specified in the provided content.

## Useful Links

- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Source / App Page:** https://mcp.pipedream.com/app/sensibo
- **Configuration Page:** /configuration (relative to the Pipedream MCP site)
- **Provider:** Pipedream Connect (https://pipedream.com/connect)