# Aero Workflow MCP Server

MCP Server for Aero Workflow, enabling MCP-based access to Aero’s workflow and practice management features for accounting firms.

---

## Overview
Aero Workflow MCP Server integrates Aero’s cloud-based workflow and practice management system for accounting firms with MCP-compatible applications (such as chat clients). It exposes Aero’s capabilities through a standard MCP server endpoint so you can connect, authenticate, and operate on client workflows from your tools.

---

## Features
- **MCP-based access to Aero Workflow**  
  - Connect Aero Workflow as a Model Context Protocol (MCP) server to supported clients.
  - Use a single, static MCP server URL for all clients (`https://mcp.pipedream.net/v2`).

- **Workflow & practice management for accounting firms**  
  - Built around the needs of cloud-based accounting practices.  
  - Access Aero’s workflow and practice management features via MCP (e.g., managing client work, tasks, and practice operations) when exposed by the configured tools.

- **Multi-client support**  
  - One server URL works for every Aero client; specific client access is controlled at authentication/connection time.

- **Chat client integration**  
  - Can be added to compatible chat-based applications as an MCP server so users can interact with Aero Workflow from within those clients.

- **Configurable via Pipedream**  
  - Configuration guided through the Pipedream interface: connect your Aero account, select a client, and expose tools.  
  - Tools (actions) are loaded dynamically from Pipedream once configured.

- **Standardized authentication**  
  - Authentication occurs when adding the MCP server to your application, allowing secure access to Aero data per account/client.

---

## Technical Details
- **MCP server endpoint**: `https://mcp.pipedream.net/v2`  
- **Provider**: Pipedream (hosting and MCP tooling integration)

---

## Pricing
No pricing information is provided in the available content.