# Brevo MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Brevo  
**Slug:** `brevo-mcp-server`

Brevo MCP Server is an MCP server integration that lets MCP-compatible clients and workflows orchestrate Brevo-powered communications across email, SMS, chat, and other customer engagement channels.

---

## Features

- **MCP server integration for Brevo**  
  - Exposes Brevo functionality via the MCP (Model Context Protocol) so MCP-aware tools and workflows can interact with Brevo.
- **Multi-channel campaign orchestration**  
  - Designed to support workflows that coordinate:  
    - Email campaigns  
    - SMS messaging  
    - Chat-based communication  
    - Other Brevo-supported channels for customer relationship management.
- **Static MCP server endpoint**  
  - Single, reusable MCP server URL for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Same endpoint is used across different MCP-compatible chat clients and tools.
- **Client-agnostic usage**  
  - Can be added to multiple MCP-enabled chat clients and applications.  
  - Works with any client that supports configuring an MCP server endpoint.
- **Authentication handled on client setup**  
  - Authentication occurs when adding the MCP server to an application or client, keeping the public endpoint static.
- **Configuration resources**  
  - Documentation and examples for adding the server to different chat clients are available via the configuration page (linked from the app page).

---

## How to Use

1. Configure an MCP-compatible client or application to use the Brevo MCP Server.  
2. Set the MCP server URL to: `https://mcp.pipedream.net/v2`.  
3. Complete authentication when prompted by your client.  
4. Use your MCP client’s tools / commands to orchestrate Brevo email, SMS, chat, and multi-channel campaigns.

---

## Pricing

No explicit pricing information for the Brevo MCP Server integration is provided in the available content.