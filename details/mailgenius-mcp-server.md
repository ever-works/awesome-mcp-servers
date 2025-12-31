# MailGenius MCP Server

**Category:** Testing & Debugging Tools  
**Brand:** MailGenius  
**Slug:** `mailgenius-mcp-server`

Free email spam-checking and deliverability testing MCP server, providing MCP clients with tools to evaluate email quality, spam risk, and deliverability.

---

## Features

- **MCP-compatible server**  
  - Exposed as a Model Context Protocol (MCP) server for integration with MCP-compatible chat or AI clients.  
  - Single static server endpoint for all clients:  
    - `https://mcp.pipedream.net/v2`

- **Email spam checking**  
  - Runs spam checks on email content.  
  - Provides an email spam score to gauge likelihood of being flagged as spam.

- **Email deliverability testing**  
  - "Mail Tester" style deliverability tests to evaluate how well an email is likely to reach inboxes.  
  - Helps assess and improve overall email quality and deliverability.

- **Workflow integration**  
  - Designed for email quality workflows inside MCP-enabled clients.  
  - Can be used programmatically within chat-based tooling to validate emails before sending.

- **Universal client URL**  
  - Static URL works for every supported MCP client.  
  - Authentication handled when adding the server to your application.

- **Configuration resources**  
  - Documentation via a configuration page (linked from the source) for setup within various chat clients.

---

## Technical Details

- **Server URL:** `https://mcp.pipedream.net/v2`  
- **Integration type:** MCP server (Model Context Protocol)  
- **Primary use cases:** email spam scoring, deliverability testing, email quality analysis.

---

## Pricing

- The service is described as a **Free Email SpamChecker**.  
- No additional paid plans or pricing tiers are listed in the provided content.