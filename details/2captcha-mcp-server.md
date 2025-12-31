# 2captcha MCP Server

**Category:** Security & Attestation MCP Servers  
**Brand:** 2captcha  
**Slug:** `2captcha-mcp-server`

MCP server that connects MCP-compatible clients to 2captcha’s CAPTCHA solving services, enabling automated offloading of CAPTCHA challenges within workflows.

---

## Features

- **MCP-compatible server**: Exposes 2captcha’s CAPTCHA solving capabilities through the Model Context Protocol (MCP), so any MCP client can integrate it.
- **Central server endpoint**: Uses a single static base URL for all clients:
  - `https://mcp.pipedream.net/v2`
- **Supports multiple CAPTCHA types**: Designed to work with 2captcha’s range of CAPTCHA types (e.g., image CAPTCHAs and other common variants; exact types depend on your 2captcha account capabilities).
- **Programmatic CAPTCHA offloading**: Lets automated workflows delegate CAPTCHA solving to 2captcha instead of requiring manual human input.
- **Client-agnostic integration**: Can be added to different MCP-enabled chat or automation clients; configuration is handled at the client level.
- **Authentication at connection time**: You authenticate when adding the MCP server to your application, using your chosen client’s configuration flow.
- **Hosted by Pipedream**: Server is provided via Pipedream Connect infrastructure, so you do not need to self-host the MCP server.

---

## Configuration & Integration

- **Server URL to configure in clients**: `https://mcp.pipedream.net/v2`
- **Setup flow**:
  - Add a new MCP server in your client.
  - Use the static URL above.
  - Complete authentication as prompted by the client.
  - Optionally consult the broader Pipedream MCP configuration docs (via the “Configuration page” referenced in the content).

---

## Pricing

- The provided content does not include any pricing or plan details for the 2captcha MCP Server or underlying 2captcha usage.
- Actual costs and plans (if any) must be obtained from 2captcha and/or Pipedream directly.