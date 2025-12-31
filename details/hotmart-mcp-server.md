# Hotmart MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Hotmart  
**Slug:** `hotmart-mcp-server`

An MCP server that connects to Hotmart’s creator monetization platform, exposing product, sales, and customer data to MCP-compatible clients for automation and analytics workflows.

---

## Features

- **Hotmart platform integration**
  - Connects to Hotmart’s creator monetization platform.
  - Provides access to product, sales, and customer data.
  - Designed for use with MCP-compatible chat and automation clients.

- **Static MCP endpoint**
  - Single shared MCP server URL for all clients:
    - `https://mcp.pipedream.net/v2`
  - Authentication is handled when adding the server to your application.

- **Client-agnostic setup**
  - The same MCP URL works across different chat clients that support MCP.
  - Can be added to various MCP-enabled applications for data-driven workflows.

- **Automation and analytics use cases**
  - Enables automation based on Hotmart product and sales events.
  - Supports analytics scenarios by exposing structured product and customer data to MCP clients.

- **Configuration documentation**
  - Full configuration details available via the platform’s Configuration page (how to add and authenticate the MCP server in clients).

---

## Technical Details

- **MCP endpoint:** `https://mcp.pipedream.net/v2`
- **Protocol:** Model Context Protocol (MCP) for server–client integration.
- **Auth model:** Authentication occurs during server addition in the client (no per-user URL changes required).

---

## Pricing

No pricing information is provided in the available content.