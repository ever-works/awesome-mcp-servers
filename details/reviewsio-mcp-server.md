# Reviews.io MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Reviews.io

An MCP (Model Context Protocol) server integration that connects Reviews.io with compatible chat or AI applications, enabling review-related workflows through a unified MCP endpoint.

---

## Features

- **Unified MCP Endpoint**  
  - Uses a single static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL works for all Reviews.io clients; authentication is handled at the application level.

- **Reviews.io Account Connection**  
  - Connects to a Reviews.io account via Pipedream.  
  - Supports client selection after account connection (for organizations managing multiple clients/brands).

- **MCP Integration for Chat/AI Clients**  
  - Designed to be added as an MCP server in compatible chat or AI applications.  
  - Allows those clients to access Reviews.io-related tools and actions exposed via MCP.

- **Tool & Action Exposure**  
  - Exposes available Reviews.io tools/actions over MCP (e.g., for review collection and management).  
  - Tools are auto-discovered/loaded by the MCP client ("Loading actions...", "Loading available tools...").

- **Configuration Guidance**  
  - Provides basic instructions to:  
    - Copy and use the static MCP server URL.  
    - Add the MCP server to different chat clients.  
  - Links to a more detailed configuration page for advanced setup.

---

## Pricing

Pricing details are not specified in the provided content. Refer to the Pipedream or Reviews.io website for current pricing and plan information.

---

## Links

- Source / Setup page: https://mcp.pipedream.com/app/reviews_io
- MCP server URL: `https://mcp.pipedream.net/v2`
- Configuration docs: /configuration (on Pipedream)