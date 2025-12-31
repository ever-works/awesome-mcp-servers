# Unthread MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Unthread  
**Slug:** `unthread-mcp-server`

## Overview
Unthread MCP Server is a Model Context Protocol (MCP) server that connects AI applications to Unthread’s AI-powered ticketing system in Slack. It enables AI systems to treat Slack conversations as structured support tickets that can be tracked, prioritized, assigned, and resolved programmatically.

## Features
- **AI-powered ticketing in Slack**  
  - Automatically tracks Slack conversations as support tickets.  
  - Uses AI to help prioritize, assign, and resolve tickets.

- **MCP server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`.  
  - Same URL works for all clients; authentication handled when adding the server to an application.

- **Integration with chat clients**  
  - Designed to be added as a server to compatible AI/chat clients that support MCP.  
  - Configuration guidance available via a dedicated configuration page.

- **Unthread account connectivity**  
  - Connects to an existing Unthread account.  
  - Supports selecting the relevant Unthread client/workspace during setup.

- **Tools exposure via MCP**  
  - Exposes Unthread actions and tools over MCP so AI agents can operate on tickets (e.g., create, update, or manage tickets) from within the client that connects to the server.

## Configuration
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
- Add the server to an MCP-compatible app or chat client.  
- Authenticate with your Unthread account and select the desired client/workspace.  
- Optional: refer to the full configuration page on the host site for client-specific setup steps.

## Pricing
No pricing information is provided in the available content.