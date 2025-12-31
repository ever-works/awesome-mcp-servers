# Joplin MCP Server

**Category:** Document Management MCP Servers  
**Brand:** Joplin  
**Slug:** `joplin-mcp-server`

Joplin MCP Server is an MCP (Model Context Protocol) server that connects AI agents to Joplin, the open‑source note‑taking application. It allows agents to create and manage notes, notebooks, and other Joplin data through a standardized MCP endpoint.

---

## Features

- **MCP-compatible server**
  - Exposes a Model Context Protocol server endpoint for integration with MCP-capable chat or AI clients.

- **Static server URL**
  - Single shared endpoint for all clients:  
    `https://mcp.pipedream.net/v2`
  - Same URL works across different chat / AI applications.

- **Joplin integration**
  - Connects directly to Joplin, the open-source note‑taking app.
  - Designed so AI agents can create and manage:
    - Notes
    - Notebooks
    - Other Joplin data (as supported by the underlying Joplin API).

- **Authentication handled at client setup**
  - Authentication occurs when you add the MCP server to your application.
  - No per-client custom URL required; auth is tied to how the client is configured.

- **Multi-client usage**
  - Intended to be added to various chat / AI clients that support MCP.
  - Configuration guidance is available per client type via the referenced configuration page.

- **Cloud-hosted by Pipedream Connect**
  - Server is hosted and provided via Pipedream’s infrastructure.
  - No self-hosted MCP server setup required for basic use.

---

## Configuration & Usage

- **Server URL:**
  - Use `https://mcp.pipedream.net/v2` as the MCP server endpoint in your client.
- **Client setup:**
  - Add the MCP server in your chat / AI client following that client’s MCP configuration instructions.
  - Full instructions are available on the provider’s Configuration page (not reproduced here).

---

## Pricing

- The provided content does not list any pricing or plans for the Joplin MCP Server. Pricing details are not available based on the current information.