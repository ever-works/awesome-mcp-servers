# Teamwork Desk MCP Server

Ticketing system MCP server that exposes the Teamwork Desk customer support and ticketing APIs through the Model Context Protocol (MCP), allowing AI agents or MCP‑compatible clients to work with support tickets programmatically.

---

## Basic Information

- **Name:** Teamwork Desk MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Brand:** Teamwork  
- **Source URL:** https://mcp.pipedream.com/app/teamwork_desk  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

---

## Description

Teamwork Desk MCP Server provides an MCP interface to the Teamwork Desk ticketing system. It enables AI agents and other MCP clients to manage customer support workflows, such as handling tickets and customer queries, directly via the MCP protocol instead of calling the underlying APIs manually.

---

## Features

- **MCP-compatible ticketing interface**  
  Exposes Teamwork Desk’s ticketing capabilities through the standard MCP protocol for easy integration with MCP-enabled chat or agent clients.

- **Programmatic ticket management**  
  Intended to let AI agents and tools manage support tickets and customer queries in Teamwork Desk programmatically (e.g., creating, reading, or updating tickets). *(Specific endpoints are not detailed on the page, but the server is described as an interface to the ticketing system.)*

- **Static server endpoint**  
  Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) that works across all supported MCP clients.

- **Client-agnostic configuration**  
  The same MCP server URL is used for every client; configuration is done in the respective chat or agent client by adding this server.

- **Authentication at client setup**  
  Authentication occurs when adding the server to an application or chat client (exact auth method not detailed on the page).

- **Documentation & configuration guidance**  
  A separate Configuration page is referenced for detailed setup steps for different chat clients.

---

## Integration & Usage

- **How to start**  
  1. Use the MCP server URL: `https://mcp.pipedream.net/v2`.  
  2. Add this MCP server to your MCP-compatible chat or agent client.  
  3. Authenticate within your client during setup.  
  4. Follow the linked configuration documentation for client-specific instructions.

---

## Pricing

- The provided content does **not** list any pricing or plans for the Teamwork Desk MCP Server. Pricing information is not available from this page.

---

## Tags

- helpdesk  
- ticketing  
- customer-support
