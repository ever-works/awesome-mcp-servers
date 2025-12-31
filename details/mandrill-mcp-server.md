# Mandrill MCP Server

**Description:**
MCP Server integration for Mandrill (Mailchimp’s transactional email API), allowing MCP clients to send and manage transactional emails.

**Category:**
- Messaging MCP Servers

**Tags:**
- Transactional email  
- Email  
- Communications

**Source URL:**
- https://mcp.pipedream.com/app/mandrill

---

## Features
- Provides an MCP-compatible server interface for Mandrill (Mailchimp’s transactional email API).
- Enables MCP clients (e.g., AI/chat tools that support MCP) to send transactional emails via Mandrill.
- Supports management of transactional email operations through MCP (subject to Mandrill API capabilities and client implementation).
- Uses a single static MCP server base URL for all clients:
  - `https://mcp.pipedream.net/v2`
- Authentication is handled when adding/configuring the server in your MCP-compatible application (credentials not embedded in the URL).
- Can be added to a variety of MCP-capable chat or agent clients (e.g., model/tooling hosts that support MCP servers).
- Centralized configuration and reference via Pipedream’s MCP configuration documentation.

---

## Integration & Usage
- **MCP Server URL:**
  - `https://mcp.pipedream.net/v2` (identical for all clients; per-client auth required).
- **Setup flow (high level):**
  1. Copy the MCP server URL.
  2. Add it as an MCP server in your chat/agent client that supports MCP.
  3. Configure authentication/credentials for Mandrill within that client or via environment configuration.
  4. Use the client’s tools/commands to send and manage transactional emails through Mandrill.
- **Documentation reference:**
  - Additional configuration details available on the Pipedream MCP Configuration page (linked from the source page).

---

## Pricing
- Not specified in the provided content. Pricing may depend on Mandrill/Mailchimp and/or Pipedream terms; refer to their official sites for details.