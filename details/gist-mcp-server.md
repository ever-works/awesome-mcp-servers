# Gist MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Gist

Gist MCP Server integrates the Gist customer engagement platform (live chat, email marketing automation, and event tracking) into MCP-compatible clients via a unified server endpoint.

---

## Description
Gist MCP Server is an MCP (Model Context Protocol) server that connects MCP-enabled applications with Gist’s customer engagement capabilities. It lets you use Gist’s live chat, email marketing automation, and event tracking from within MCP clients through a single, static server URL.

---

## Features
- **MCP integration**
  - Exposes Gist functionality through a standard MCP server endpoint.
  - Compatible with any MCP client that can connect to a static MCP server URL.

- **Single static server URL**
  - Uses a single static URL for all clients: `https://mcp.pipedream.net/v2`.
  - Authentication occurs when adding the server to your application, not by changing the URL.

- **Live chat integration**
  - Connects MCP clients to Gist’s live chat capabilities to support real-time customer communication (as provided by Gist’s platform).

- **Email marketing automation**
  - Provides access to Gist’s email marketing automation tools via MCP.
  - Supports automated email flows managed through Gist (details configured in Gist, exposed via the MCP server).

- **Event tracking**
  - Integrates Gist’s event tracking so MCP clients can work with behavioral and engagement data tracked in Gist.

- **Works across multiple chat clients**
  - Can be added to different MCP-enabled chat clients using the same server URL.
  - Each client authenticates individually when the server is added.

- **Configuration resources**
  - Full configuration guidance available via a dedicated configuration page (linked from the server page).

---

## Technical Details
- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Integration platform:** Powered by Pipedream Connect
- **Authentication:** Per-client, performed when adding the server to an MCP application

---

## Pricing
The provided content does not list any pricing or plans for Gist MCP Server.

---

## Links
- Source / App page: https://mcp.pipedream.com/app/gist
- Configuration documentation: /configuration (as referenced on the page)
- Terms: https://pipedream.com/terms
- Privacy Policy: https://pipedream.com/privacy