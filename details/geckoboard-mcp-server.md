# Geckoboard MCP Server

**Category:** Data Visualization  
**Tags:** dashboards, KPI, reporting

Geckoboard MCP Server is an MCP (Model Context Protocol) server that allows MCP-compatible clients (such as chat-based tools) to programmatically interact with Geckoboard dashboards, metrics, KPIs, and visualizations.

---

## Features

- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Designed to work with any MCP client that supports adding external servers.

- **Geckoboard integration**  
  - Enables interaction with Geckoboard dashboard data, including metrics, KPIs, and visualizations (as indicated by the product description).  
  - Intended for teams and businesses to surface and share analytics data in an understandable format.

- **Account-based configuration**  
  - Requires connecting a Geckoboard (via Pipedream) account before use.  
  - Account is checked/validated during setup.

- **Client-agnostic setup**  
  - Works with multiple MCP clients (e.g., different chat or agent applications).  
  - Users select their specific client and follow tailored connection instructions.

- **Central configuration documentation**  
  - A dedicated configuration page (linked as “Configuration page”) describes how to add and authenticate the server within compatible apps.

- **Tool/action discovery via MCP**  
  - Once connected, clients can load and list available MCP tools/actions exposed by the Geckoboard integration (shown as “Loading actions…”, “Loading available tools…”).

---

## Setup & Usage

1. Connect a Geckoboard/Pipedream account.  
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add the server URL in your MCP-compatible client (e.g., a chat app or development environment).  
4. Authenticate when prompted by your client.  
5. Use the client’s interface to discover and run available Geckoboard-related tools/actions.

---

## Pricing

- No pricing information is provided in the available content. Use of the Geckoboard MCP Server may depend on underlying Pipedream and/or Geckoboard account plans.