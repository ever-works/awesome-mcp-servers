# WhatsAble MCP Server

An MCP server integration for WhatsAble that exposes APIs to send customized WhatsApp messages from MCP-compatible apps.

---

## Overview
- **Type:** MCP server / messaging integration
- **Category:** Messaging MCP Servers
- **Platform:** Pipedream
- **Primary use case:** Programmatically send customized WhatsApp messages via MCP-accessible APIs.

---

## Features
- **MCP-compatible WhatsApp messaging API**  
  - Provides an MCP-accessible API endpoint to trigger WhatsApp messages.  
  - Designed to send customized WhatsApp messages from tools that support the Model Context Protocol.

- **Static MCP server URL**  
  - Single, static server URL for all clients: `https://mcp.pipedream.net/v2`.  
  - Same URL can be reused across different chat clients and applications.

- **Account connection & configuration**  
  - Connect a WhatsAble / Pipedream account to enable messaging capabilities.  
  - Select the relevant client within the configuration flow to start using the server.  
  - Additional configuration details available via a dedicated configuration page (on Pipedream).

- **Multi-client support**  
  - Intended to work with multiple chat clients that support MCP.  
  - Each client can be configured to use the same MCP server URL with its own authentication.

- **Authentication at app level**  
  - Authentication occurs when adding the MCP server to your application rather than via different URLs per client.

---

## Integration & Usage
- Add the static MCP server URL (`https://mcp.pipedream.net/v2`) to your MCP-compatible app or chat client.
- Authenticate within the app to link your account.
- Use the exposed tools / actions (loaded from the MCP server) to send customized WhatsApp messages.

---

## Pricing
- Not specified in the provided content.