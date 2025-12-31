# InfoLobby MCP Server

## Overview
InfoLobby MCP Server is an MCP (Model Context Protocol) server that connects to InfoLobby, a cloud‑hosted database platform for structured data management. It provides a static server endpoint that can be added to compatible chat or MCP‑enabled applications to work with InfoLobby data.

- **Type:** MCP server / integration
- **Category:** Database, cloud, data management
- **Brand:** InfoLobby
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Cloud database integration**: Connects applications to InfoLobby, a hosted database for structured data.
- **Static MCP endpoint**: Uses a single static URL (`https://mcp.pipedream.net/v2`) for all clients.
- **Client‑agnostic setup**: The same server URL works across different chat clients and MCP‑enabled apps.
- **Authentication at connection time**: Authentication is handled when you add the server to your application, rather than per‑client URL.
- **Configuration guidance**: Provides instructions (via a configuration page) for adding the server to various supported clients.
- **Tooling via MCP**: Exposes InfoLobby actions and tools through the MCP protocol (tools list is dynamically loaded in the UI).

## Setup
1. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
2. Add the server to your MCP‑compatible app or chat client.
3. Authenticate when prompted to connect to your InfoLobby account.

## Pricing
Pricing details are not provided in the available content.