# Streamtime MCP Server

**Category:** Project Management MCP Servers  
**Tags:** project-management, time-tracking, tasks

Streamtime MCP Server is an MCP integration for the Streamtime project management platform. It enables AI-driven workflows for task management, team coordination, and time tracking through a standardized MCP server endpoint.

---

## Features

- **MCP Integration for Streamtime**  
  - Exposes Streamtime project management capabilities via the Model Context Protocol (MCP).
  - Designed to plug into MCP-compatible chat or AI clients.

- **Unified MCP Server URL**  
  - Uses a static MCP server URL: `https://mcp.pipedream.net/v2` that works for all clients.
  - Authentication handled when adding the server in the client application.

- **AI-Driven Workflows**  
  - Supports AI-assisted task management for individual workers.  
  - Enables workflows for team management for leaders.  
  - Facilitates time-tracking workflows for teams and individuals.

- **Client-Agnostic Setup**  
  - Can be added to different chat / AI clients that support MCP.  
  - Configuration guidance available via a dedicated configuration page (per-client setup instructions).

- **Tool-Based Actions (via MCP)**  
  - Provides MCP tools / actions exposed by Streamtime (loaded dynamically in the interface as "Available tools").

---

## Usage / Setup

1. Configure your Streamtime connection in the Pipedream MCP interface.  
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add this server URL to your MCP-compatible app or chat client.  
4. Authenticate when prompted in the client to start using Streamtime tools.

---

## Pricing

No pricing information is provided in the available content.