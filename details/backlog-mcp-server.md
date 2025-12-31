# Backlog MCP Server

MCP Server for the Backlog project and code management platform, providing MCP-compatible access to issues, repositories, and project data via the Backlog API.

- **Name:** Backlog (API) MCP Server
- **Category:** Project Management MCP Servers
- **Brand:** Backlog
- **Source URL:** https://mcp.pipedream.com/app/backlog_api
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Description
The Backlog MCP Server exposes the Backlog project and code management platform via an MCP-compatible interface. It enables chat-based or tool-based clients to interact with Backlog issues, repositories, and project data through the Backlog API, using a static MCP server endpoint.

## Features
- **MCP-compatible server for Backlog**  
  Provides an MCP Server that integrates Backlog’s project and code management capabilities into MCP-enabled clients.

- **Access to Backlog project data**  
  Designed to work with Backlog’s project data (projects, issues, and related information) through the Backlog API.

- **Issues & repositories integration**  
  Intended to provide access to Backlog issues and repositories, enabling workflows around issue tracking and code management.

- **Static MCP server URL**  
  Uses a single static endpoint that can be added to any MCP-compatible client:  
  `https://mcp.pipedream.net/v2`

- **Per-client authentication**  
  Authentication is performed when adding the server to each client / application, allowing the same server URL to be reused across tools.

- **Client-agnostic setup**  
  Works with multiple chat or MCP clients; users select their chat client and follow setup instructions (via the configuration documentation).

- **Backed by Pipedream Connect**  
  The server is powered by Pipedream Connect’s infrastructure for MCP servers.

## Configuration & Usage
- Add the MCP server to your client using the static URL: `https://mcp.pipedream.net/v2`.
- Authenticate with Backlog when prompted by your client during setup.
- Refer to the Pipedream **Configuration** page for step-by-step instructions (client-specific guidance is provided there).

## Pricing
- No pricing information is provided in the available content.