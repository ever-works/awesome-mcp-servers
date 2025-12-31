# Zixflow MCP Server

**Description**

Zixflow MCP Server is an MCP (Model Context Protocol) server that connects AI assistants to Zixflow’s AI-powered CRM and multi-channel messaging capabilities. It enables interactions with CRM data and messaging channels such as SMS, email, and WhatsApp through a standardized MCP endpoint.

---

## Key Details

- **Name:** Zixflow MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Brand:** Zixflow  
- **MCP Endpoint URL:** `https://mcp.pipedream.net/v2`

---

## Features

- **AI-CRM Integration**  
  - Connects an AI client to Zixflow’s CRM functionality.  
  - Designed to support AI-driven CRM workflows and interactions (e.g., retrieving or acting on CRM-related data via MCP tools).

- **Multi-Channel Messaging Support**  
  - Provides access to messaging across:  
    - SMS  
    - Email  
    - WhatsApp

- **Standard MCP Server Endpoint**  
  - Uses a single static server URL (`https://mcp.pipedream.net/v2`) that works for all clients.  
  - Authentication occurs when the server is added/connected in the client application.

- **Client-Agnostic Setup**  
  - Can be added to different MCP-compatible chat or AI clients.  
  - Configuration guidance is provided per client type via the Pipedream interface.  
  - Additional configuration details are available on a dedicated configuration page (linked from the UI).

- **Account Connection Flow**  
  - Requires connecting a Zixflow account within the Pipedream-based UI.  
  - Once connected, users can select the appropriate client and begin using available MCP tools.

- **Tool-Based Actions (MCP Tools)**  
  - Exposes actions (tools) through MCP for CRM and messaging operations.  
  - Tools are dynamically loaded within the Pipedream interface (e.g., “Loading actions…”, “Loading available tools…”), indicating a tool catalog accessible via the server.

---

## Configuration & Usage

- **Connect Zixflow Account:** Configure and authenticate your Zixflow account in the Pipedream UI.  
- **Copy MCP URL:** Use `https://mcp.pipedream.net/v2` as the MCP server endpoint in your AI/chat client.  
- **Add to Client:** Add the server to your MCP-compatible application and complete authentication there.  
- **Discover Tools:** Once connected, query or browse the available tools/actions for CRM and messaging.

---

## Pricing

- No pricing information is provided in the available content.