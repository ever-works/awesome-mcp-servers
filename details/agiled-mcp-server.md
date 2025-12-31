# Agiled MCP Server

All-in-one business management platform MCP server for exposing Agiled data to AI agents.

## Overview
- **Type:** MCP Server (Model Context Protocol)
- **Platform:** Agiled (business management)
- **Purpose:** Exposes Agiled CRM, project, and operations data to AI agents / MCP-compatible clients.
- **Provider:** Pipedream Connect
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **Unified business data access**
  - Connects to Agiled’s all-in-one business management platform.
  - Provides a single MCP endpoint for multiple Agiled modules (CRM, projects, operations).

- **CRM integration**
  - Access to customer and contact records via MCP.
  - Designed for use by AI agents to query and work with CRM data.

- **Project management integration**
  - Exposure of project-related data (e.g., projects, tasks, related entities) through MCP.

- **Operations data integration**
  - Access to broader business operations data from Agiled via MCP.

- **Static MCP server URL**
  - Uses a single static URL for all clients: `https://mcp.pipedream.net/v2`.
  - Authentication is handled when adding the server to the client, not via different URLs.

- **Client-agnostic setup**
  - Works with any MCP-compatible chat or AI client.
  - Configuration instructions are available via the platform’s configuration page.

## Usage
- Add `https://mcp.pipedream.net/v2` as an MCP server in a supported chat / AI client.
- Authenticate with Agiled when prompted by the client.
- Use the client’s MCP tooling to query CRM, project, and operations data from Agiled.

## Pricing
- Not specified in the provided content.