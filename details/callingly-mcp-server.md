# Callingly MCP Server

Callingly MCP Server is an MCP (Model Context Protocol) server integration that connects Callingly with compatible chat or AI clients, enabling automatic call initiation when new leads arrive.

---

## Overview
- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Provider:** Callingly, powered by Pipedream Connect
- **Primary Function:** Automatically calls you and dials new leads as soon as they are received, accessible via a standard MCP endpoint.

---

## Features
- **Automatic Lead Calling**
  - Triggers calls automatically when a new lead is received in Callingly.
  - Dials the new lead for you without manual intervention.

- **Standard MCP Endpoint**
  - Uses a static MCP server URL: `https://mcp.pipedream.net/v2`.
  - Same endpoint works for all supported MCP clients.

- **Authentication at Client Setup**
  - Authentication is performed when adding the MCP server to your application or chat client.

- **Multi‑Client Compatibility**
  - Can be added to multiple MCP-compatible chat or AI clients.
  - Setup instructions are provided per client type via the configuration resources.

- **Centralized Configuration**
  - Full configuration details available through a shared configuration page (e.g., environment variables, auth, and connection details managed in one place).

- **Pipedream Connect Integration**
  - Runs on Pipedream’s infrastructure, leveraging Pipedream Connect for connectivity and management.

---

## Setup
1. **Copy MCP Server URL**  
   Use: `https://mcp.pipedream.net/v2`.
2. **Add to Your Client**  
   Add this URL as an MCP server in your chat or AI client.
3. **Authenticate**  
   Complete authentication when prompted by your client.
4. **Configure Details (If Needed)**  
   Refer to the configuration page linked from the service for any advanced settings.

---

## Pricing
The provided content does not specify any pricing or plans for Callingly MCP Server. Consult Callingly or Pipedream documentation or dashboards for current pricing details.

---

## Links
- **Source / App Page:** https://mcp.pipedream.com/app/callingly
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Configuration Info:** Accessible via the referenced configuration page in the app
- **Pipedream Connect:** https://pipedream.com/connect
- **Terms:** https://pipedream.com/terms
- **Privacy Policy:** https://pipedream.com/privacy