# Epsy MCP Server

**Category:** Security & Attestation MCP Servers  
**Brand:** Epsy

An MCP server for Epsy that enables online verification capabilities for MCP-compatible agents and tools, exposed via a static MCP endpoint.

---

## MCP Endpoint

- **Server URL:** `https://mcp.pipedream.net/v2`  
  - Static URL that works for all MCP-compatible clients.
  - Authentication is performed when adding the server to your application.

---

## Features

- **Online verification capabilities**
  - Provides verification functions for agents and tools that support the MCP (Model Context Protocol).
  - Designed as a security / compliance / verification layer that tools can call at runtime.

- **MCP-compatible server**
  - Implements the MCP protocol so it can be added as a server in MCP-aware chat clients and applications.
  - Suitable for use by multiple MCP clients through a single shared endpoint.

- **Static, reusable server URL**
  - Single URL (`https://mcp.pipedream.net/v2`) used across clients and environments.
  - Simplifies configuration and deployment for different chat clients or tools.

- **App integration flow**
  - Add the server to your chat client or MCP-enabled app using the static URL.
  - Authentication is handled during the “add server” step in the client/app.

- **Configuration documentation**
  - Additional setup and integration details are available via a dedicated Configuration page (linked from the product page).

---

## Pricing

- Not specified in the provided content.