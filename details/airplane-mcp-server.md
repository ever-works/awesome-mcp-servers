# Airplane MCP Server

An MCP (Model Context Protocol) server that connects to Airplane, letting you turn APIs, SQL queries, and scripts into internal apps that MCP-enabled agents and tools can use.

---

## Overview
- **Type:** MCP Server (workflow automation / internal tools)
- **Purpose:** Expose Airplane-based APIs, SQL queries, and scripts as internal applications accessible via MCP-compatible clients (e.g., chat-based or agentic tools).
- **Provider:** Pipedream (via Pipedream Connect)
- **Static MCP Endpoint:** `https://mcp.pipedream.net/v2`

---

## Features
- **Airplane Integration**
  - Connects to Airplane to turn:
    - APIs
    - SQL queries
    - Scripts
    into internal apps.

- **MCP-Compatible Server**
  - Implements the MCP protocol so agents and tools that support MCP can call Airplane workflows as tools.
  - Provides a single static server URL usable across different MCP clients.

- **Static MCP Server URL**
  - Uses a fixed endpoint: `https://mcp.pipedream.net/v2`.
  - Same URL works for all supported clients.
  - Authentication is handled when adding the server inside each client / application.

- **Multi-Client Support**
  - Designed to be added to various chat or agent clients that support MCP.
  - Configuration guidance available per client via the configuration page (not reproduced here).

- **Internal App Abstraction**
  - Wraps lower-level resources (APIs, SQL, scripts) as higher-level internal apps for non-technical or less-technical users via MCP-enabled interfaces.

- **Pipedream Connect Backing**
  - Runs on Pipedream Connect infrastructure.
  - Benefits from Pipedream’s integration and workflow capabilities behind the scenes (no additional setup details provided in the source).

---

## Usage
- **Add MCP Server to a Client**
  - Use the static URL: `https://mcp.pipedream.net/v2` when configuring the MCP server in your chat or agent client.
  - Authenticate during the client-side setup flow (method depends on the specific client).

---

## Pricing
- The provided content does not include any pricing or plan details for the Airplane MCP Server.
