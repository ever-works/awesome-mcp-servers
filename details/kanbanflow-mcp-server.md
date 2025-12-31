# KanbanFlow MCP Server

## Overview
KanbanFlow MCP Server is an MCP (Model Context Protocol) integration for KanbanFlow, a Lean project management tool that supports real-time team collaboration and Pomodoro-based time tracking. It exposes KanbanFlow functionality to MCP-compatible clients via a static server endpoint.

- **Category:** Project management MCP server
- **Integration type:** MCP Server (via Pipedream Connect)
- **Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Lean project management integration**
  - Connects MCP clients to KanbanFlow’s Lean project management capabilities.
  - Enables working with Kanban-style workflows through MCP-compatible tools (where supported by the client and integration).

- **Real-time collaboration support**
  - Integrates with KanbanFlow’s real-time collaboration features so multiple team members can interact with the same boards and tasks concurrently (subject to KanbanFlow’s own capabilities).

- **Pomodoro-based time tracking**
  - Exposes KanbanFlow’s Pomodoro technique–based time tracking through an MCP server, making it available in compatible clients and automations.

- **Single static MCP endpoint**
  - Uses a single, static MCP server URL (`https://mcp.pipedream.net/v2`) for all MCP clients.
  - Authentication is handled when adding the server within each application/client.

- **Client-agnostic setup**
  - Designed to work with any MCP-compatible chat or development client.
  - Configuration is handled per client, using the same server URL.

## Usage Notes
- Add the MCP server to your MCP-compatible app using:
  - **Server URL:** `https://mcp.pipedream.net/v2`
- You’ll authenticate to KanbanFlow during or after adding the server, depending on your client’s flow.

## Pricing
No pricing information is provided in the available content.