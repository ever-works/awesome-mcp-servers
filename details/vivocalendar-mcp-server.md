# Vivocalendar MCP Server

An MCP (Model Context Protocol) server that exposes Vivocalendar’s all‑in‑one appointment scheduling capabilities over a standard MCP endpoint.

---

## Overview
- **Name:** Vivocalendar MCP Server  
- **Category:** Business Management / Appointment Scheduling  
- **Protocol:** MCP (Model Context Protocol)  
- **Provider / Host:** Pipedream  
- **Purpose:** Make Vivocalendar’s scheduling and calendar functionality accessible to MCP‑compatible applications (e.g., chat clients, AI assistants).

---

## Features
- **MCP server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Single endpoint usable across all clients.

- **Account-based configuration**  
  - Connect a Vivocalendar account through Pipedream.  
  - Select a specific client / configuration after connecting the account.

- **Authentication at client setup**  
  - Authentication occurs when adding the MCP server to an application, not per‑URL.

- **Multi‑client compatibility**  
  - Designed to be added to different chat or MCP‑enabled clients.  
  - Client-specific setup instructions available via the interface.

- **Tool exposure over MCP**  
  - Exposes Vivocalendar’s appointment scheduling and calendar tools as MCP actions (listed as “Available tools” in the interface).  
  - Tools are loaded dynamically once the account is configured.

- **Configuration documentation**  
  - Additional setup and configuration guidance available via a dedicated configuration page on Pipedream.

---

## Integration & Setup
1. Connect a Vivocalendar account inside Pipedream.  
2. Copy the static MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add this URL as an MCP server in a supported chat client or MCP‑compatible app.  
4. Authenticate when prompted in the client.  
5. Use the exposed tools to perform appointment and calendar operations via MCP.

---

## Pricing
- No pricing information is provided in the available content.
