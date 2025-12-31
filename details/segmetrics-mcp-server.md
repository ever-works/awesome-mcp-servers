# SegMetrics MCP Server

SegMetrics MCP Server connects your chat or MCP-compatible applications to SegMetrics’ marketing analytics and attribution data, helping you understand lead origins, behavior, and revenue impact directly from your assistant environment.

---

## Overview

- **Type:** MCP Server / Integration
- **Purpose:** Provide access to SegMetrics marketing analytics and attribution data inside tools that support the Model Context Protocol (MCP).
- **Provider:** SegMetrics (delivered via Pipedream Connect)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

Use this static URL as the MCP server endpoint in your client; authentication is handled when you add the server to your application.

---

## Features

- **Unified MCP Endpoint**  
  - Single static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Works for every client that supports MCP.  
  - Authentication performed during server setup in the client.

- **SegMetrics Data Access**  
  - Access SegMetrics’ marketing analytics and attribution data through MCP.  
  - Designed to provide clarity on:  
    - Where leads come from (lead source / origin).  
    - How leads behave over time (engagement and actions).  
    - How much marketing efforts are worth in terms of revenue impact.

- **Chat Client Integration**  
  - Can be added to compatible chat clients as an MCP server.  
  - Documentation and guidance available via a configuration page (linked from the app) for:
    - Adding the server URL to the client.
    - Completing authentication.

- **Pipedream Connect Integration Layer**  
  - Powered by Pipedream Connect as the infrastructure for the MCP server.  
  - Inherits Pipedream’s platform terms and privacy policies.

- **Multi-Client Reuse**  
  - Same MCP server URL can be reused across different MCP-aware tools or assistants, with per-client authentication.

---

## Configuration

- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Setup Steps (high level):**
  1. Add `https://mcp.pipedream.net/v2` as an MCP server in your chat client or MCP-compatible tool.
  2. Follow the client’s prompts to authenticate with SegMetrics via Pipedream.
  3. (Optionally) Refer to the linked “Configuration” page in the app for client-specific instructions.

---

## Category & Tags

- **Category:** Business & Commerce – MCP Servers
- **Tags:**
  - Marketing analytics
  - Attribution
  - Sales analytics

---

## Pricing

The provided content does not list any pricing or plans for the SegMetrics MCP Server. Pricing details would need to be obtained from SegMetrics or Pipedream directly.