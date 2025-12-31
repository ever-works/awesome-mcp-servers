# pdfFiller MCP Server

**Category:** Document Management MCP Servers  
**Brand:** pdfFiller

An MCP server that provides AI agents with access to pdfFiller’s online PDF editing and document workflow tools via a static MCP endpoint.

---

## Features

- **MCP-compatible server**  
  - Exposes pdfFiller’s PDF and document workflow capabilities to AI/chat clients through the Model Context Protocol (MCP).

- **Static server URL**  
  - Single MCP endpoint for all clients: `https://mcp.pipedream.net/v2`.
  - Same URL works across different chat applications; authentication handled when adding the server to each app.

- **Account-based configuration**  
  - Connect a pdfFiller account through the Pipedream interface.  
  - Select the appropriate client after connecting your account to begin using tools.

- **Tool discovery via MCP**  
  - Provides a set of “available tools” to the MCP client (e.g., for PDF editing and document workflows).  
  - Tools are dynamically loaded and listed by the client (shown as “Loading actions…” / “Loading available tools…” in the interface).

- **Chat client integration**  
  - Can be added to multiple chat / AI clients that support MCP.  
  - Pipedream provides per-client instructions via the “Add the server to your app” flow.

- **Configuration documentation**  
  - Central configuration guidance available through a dedicated “Configuration” page on Pipedream.

> Note: The content does not list the individual pdfFiller tools (e.g., specific edit, fill, sign actions), only that actions are loaded as available tools.

---

## Pricing

The provided content does not include any pricing or plan details for the pdfFiller MCP Server or for pdfFiller itself.

---

## Integration Details

- **Server URL:** `https://mcp.pipedream.net/v2`  
- **Authentication:** Performed when adding the MCP server to a supported application after connecting a pdfFiller account through Pipedream.
