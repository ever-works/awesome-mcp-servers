# Rocket.Chat MCP Server

An MCP Server integration for Rocket.Chat, exposing its communication and collaboration platform APIs to MCP-compatible clients.

- **Category:** Messaging MCP Servers  
- **Tags:** team-chat, collaboration, open-source  
- **Source URL:** https://mcp.pipedream.com/app/rocket_chat  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Overview
The Rocket.Chat MCP Server is a middleware integration that exposes Rocket.Chat’s communication and collaboration APIs via the Model Context Protocol (MCP). It enables MCP-compatible clients (such as AI assistants and other tools) to connect to and work with Rocket.Chat workspaces.

## Features
- **MCP-compatible endpoint**  
  - Single static MCP server URL usable across supported MCP clients: `https://mcp.pipedream.net/v2`.
- **Rocket.Chat integration**  
  - Connects MCP clients to Rocket.Chat’s team chat and collaboration platform.  
  - Designed for open-source, self-hosted, or cloud Rocket.Chat deployments (as supported by the underlying Rocket.Chat APIs).
- **Authentication at client setup**  
  - Authentication is handled when adding the server to an application or client (per client’s configuration flow).
- **Client-agnostic configuration**  
  - The same MCP server URL is used for different MCP-enabled chat clients.  
  - Additional configuration details are available via the linked configuration page (per Pipedream / client docs).

## Setup & Integration
- Use the static MCP server URL in your MCP-enabled client.  
- Follow your client’s instructions to add a new MCP server and complete authentication.  
- Optional: consult the full configuration page on Pipedream for client-specific setup steps.

## Pricing
The provided content does not list any pricing or plan details for the Rocket.Chat MCP Server. Refer to the source URL or Pipedream documentation for current pricing information, if applicable.