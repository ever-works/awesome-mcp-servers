# Cartes MCP Server

## Overview
Cartes MCP Server is a Model Context Protocol (MCP) server that exposes Cartes mapping capabilities for use in location-based and mapping-enabled applications. It provides a single static endpoint you can add to compatible MCP clients to access Cartes map data and related services.

- **Type:** MCP server (data access / integration)
- **Category:** Data Access & Integration – MCP Servers
- **Use cases:** Maps, location intelligence, integrating mapping data into AI/chat clients and other MCP-compatible applications.

## Features
- **MCP-compatible mapping server**
  - Exposes Cartes mapping capabilities via the Model Context Protocol.
  - Designed to plug into MCP-enabled chat clients and applications.

- **Static server endpoint**
  - Single MCP server URL for all supported clients: `https://mcp.pipedream.net/v2`.
  - Same endpoint used across different MCP-compatible applications.

- **Account-based configuration**
  - Connect your Cartes-related account within the Pipedream-hosted interface.
  - Configure client-specific settings after connecting your account.

- **Client-agnostic setup flow**
  - Documentation to add the server to various chat clients.
  - Central configuration page for more detailed setup instructions.

- **Tooling integration**
  - Exposes “tools” (actions) via MCP for interacting with Cartes mapping services.
  - Tools are discoverable by MCP clients once the server is configured.

## Integration & Access
- **Server URL:** `https://mcp.pipedream.net/v2`
- **Access method:**
  - Add the MCP server URL to your MCP-compatible client.
  - Authenticate when prompted by the client to complete setup.
- **Host platform:** Provided and hosted by Pipedream.

## Pricing
The provided content does not include any pricing or plan information for Cartes MCP Server.