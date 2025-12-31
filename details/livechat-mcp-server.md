# LiveChat MCP Server

**Category:** Messaging MCP Servers  
**Brand:** LiveChat  
**Slug:** `livechat-mcp-server`

An MCP Server integration for LiveChat that lets MCP-compatible clients interact programmatically with the LiveChat customer service and sales chat platform.

---

## Features

- **MCP-compatible LiveChat integration**  
  - Exposes LiveChat functionality as an MCP Server so MCP clients can use LiveChat programmatically.

- **Static MCP server endpoint**  
  - Single server URL for all clients:  
    `https://mcp.pipedream.net/v2`
  - Same URL works across different MCP chat clients; authentication is handled when adding the server to the application.

- **Account-based configuration**  
  - Connect a LiveChat account and select the corresponding client configuration within the Pipedream interface before use.

- **Client-agnostic setup**  
  - Designed to be added to multiple MCP-enabled chat clients; specific instructions are provided per client (via the "Select your chat client" flow).

- **Tooling/actions exposure**  
  - The server is designed to expose LiveChat-related tools/actions (e.g., for customer service and sales chat workflows) to MCP clients. (The page indicates tools load dynamically, though individual tools are not listed.)

- **Central configuration documentation**  
  - Additional configuration and setup details available via a dedicated configuration page on the host platform.

---

## Technical Details

- **Server type:** MCP Server for LiveChat
- **Protocol:** MCP (Model Context Protocol)
- **Base URL:** `https://mcp.pipedream.net/v2`
- **Host platform:** Pipedream

---

## Pricing

The provided content does not list any pricing or plans for the LiveChat MCP Server integration.