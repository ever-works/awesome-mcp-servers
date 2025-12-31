# Microsoft To Do MCP Server

**Category:** Project Management MCP Servers  
**Brand:** Microsoft  
**Source:** https://mcp.pipedream.com/app/microsofttodo

## Overview
The Microsoft To Do MCP Server integrates Microsoft To Do with MCP-compatible clients, enabling programmatic creation and management of to-do lists, reminders, and notes. It syncs tasks across devices and Microsoft 365 accounts so users can access planner and task manager capabilities from their preferred MCP client.

## Features
- **MCP-compatible integration**: Exposes Microsoft To Do as an MCP Server that can be added to any supported MCP client.
- **Programmatic task management**: Create and manage to-do lists, reminders, and notes via MCP tools.
- **Cross-device syncing**: Syncs lists and tasks across devices through the underlying Microsoft To Do / Microsoft 365 account.
- **Microsoft 365 account support**: Works with Microsoft 365 accounts to keep tasks aligned with a user’s existing Microsoft ecosystem.
- **Daily planner support**: Access daily planner and task manager features from within MCP-compatible chat or other clients.
- **Static MCP server URL**: Uses a single static server endpoint for all clients:
  - `https://mcp.pipedream.net/v2`
- **Per-client configuration**: Can be added to different MCP-capable chat clients; each client authenticates to the same server URL.
- **Authentication on add**: User authenticates to Microsoft To Do when adding the MCP server to their application.
- **Central configuration docs**: Additional configuration details available on the Pipedream configuration page (for setup and client-specific steps).

## Setup
- Copy the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to a supported MCP client.
- Authenticate with your Microsoft account when prompted to enable access to Microsoft To Do data.

## Pricing
The provided content does not specify any pricing or plans for the Microsoft To Do MCP Server.