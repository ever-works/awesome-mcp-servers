# Resend MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Resend  
**Source:** https://mcp.pipedream.com/app/resend

An MCP server that exposes the Resend email API over the Model Context Protocol (MCP), allowing developers and MCP-compatible clients to send and manage email via a standardized tools interface.

## Features

- **MCP-compatible email API access**  
  - Provides Resend’s developer-focused email capabilities through the MCP protocol.  
  - Designed to be used from MCP-enabled chat or agent clients.

- **Static MCP Server URL**  
  - Single, static endpoint for all supported clients:  
    - `https://mcp.pipedream.net/v2`  
  - URL is the same regardless of which MCP client you use.

- **Account-based authentication**  
  - Authentication occurs when adding the MCP server to your application / client.  
  - Uses your connected Resend account (via Pipedream) for authorization.

- **Client-agnostic configuration**  
  - Works with multiple MCP-compatible chat clients.  
  - Per-client setup instructions available via the “Select your chat client” flow.  
  - Central configuration reference via the full Configuration page.

- **Resend email capabilities (via MCP)**  
  - Interface intended for:  
    - Sending emails programmatically.  
    - Managing email sending workflows through tools exposed over MCP.  
  - Developer-focused API semantics surfaced as MCP tools (exact tool list is dynamically loaded in the UI).

## Configuration

- Connect your Resend account in the Pipedream interface.  
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
- Add the server URL to your MCP-compatible app/client.  
- Authenticate when prompted by your client.  
- (Optional) Consult the full Configuration page on Pipedream for detailed, client-specific setup steps.

## Pricing

The provided content does not list any pricing or plans for the Resend MCP Server. Consult the source page or Pipedream/Resend documentation for current pricing details.