# Mattermost MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Mattermost  
**Source:** https://mcp.pipedream.com/app/mattermost

## Overview
Mattermost MCP Server connects the open‑source Mattermost team chat platform with the Model Context Protocol (MCP), enabling agents and applications to work with self‑hosted Mattermost instances. It allows automated agents to access channels, post messages, and interact with teams within Mattermost via a standard MCP endpoint.

## Features
- **MCP Integration**
  - Provides an MCP-compliant server endpoint for Mattermost.
  - Allows MCP-compatible agents and clients to connect using a static URL.

- **Mattermost Connectivity**
  - Integrates with the open‑source Mattermost chat platform.
  - Targets self‑hosted Mattermost deployments.
  - Supports interaction with Mattermost channels and teams (e.g., reading and posting messages).

- **Static MCP Server URL**
  - Single endpoint for all clients: `https://mcp.pipedream.net/v2`.
  - Same URL works across different MCP clients.
  - Authentication is handled during server addition/configuration within the client.

- **Client-Agnostic Setup**
  - Can be added to multiple chat or agent clients that support MCP.
  - Configuration guidance is available via the referenced configuration documentation.

- **Self-Host & Open Source Alignment**
  - Designed for use with self-hosted Mattermost environments.
  - Aligns with Mattermost’s open‑source, self‑managed deployment model.

## Configuration
- Use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Configure authentication within your chosen MCP client when adding this server.
- Additional setup and client-specific instructions are available on the linked configuration page (not included here).

## Pricing
- No pricing information is provided in the available content.