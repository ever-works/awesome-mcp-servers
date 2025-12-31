# HelloLeads MCP Server

MCP Server integration for HelloLeads, providing MCP-accessible endpoints for smart lead capture and management.

---

## Overview
HelloLeads MCP Server connects the HelloLeads lead management CRM to MCP-compatible chat clients and applications via a static MCP server URL. Once configured and authenticated, it exposes HelloLeads tools and actions through the MCP protocol for streamlined lead capture and management.

---

## Features
- **MCP Server Integration**
  - Provides a static MCP server endpoint: `https://mcp.pipedream.net/v2`.
  - Works with MCP-compatible applications and chat clients.
  - Authentication is handled when adding the server to your application.

- **HelloLeads CRM Connectivity**
  - Connects to a HelloLeads account as the underlying CRM.
  - Designed for smart and simple lead management for small businesses.

- **Client Selection Flow**
  - "Configure HelloLeads" step to connect your account.
  - Select a client within your HelloLeads setup after connecting.

- **Tooling / Actions Exposure**
  - Exposes HelloLeads actions and tools as MCP tools (listed as “Available tools” / “Loading actions…” in the interface).
  - Tools become available to your chat client once the server is added and configured.

- **Configuration Guidance**
  - Workflow to copy and use the MCP server URL.
  - Option to select your chat client to see tailored setup instructions.
  - Reference to a full configuration page for detailed setup steps.

---

## Technical Details
- **MCP Endpoint**: `https://mcp.pipedream.net/v2`
- **Protocol**: Model Context Protocol (MCP) server used by compatible chat or agent clients.
- **Provider**: Hosted and integrated via Pipedream.

---

## Pricing
No pricing information is provided in the available content.