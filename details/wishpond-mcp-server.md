## Wishpond MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Wishpond  
**Slug:** wishpond-mcp-server

### Overview
The Wishpond MCP Server exposes Wishpond’s all‑in‑one marketing platform over the Model Context Protocol (MCP), allowing compatible applications (such as chat clients or agent frameworks) to create and manage marketing campaigns, landing pages, and lead flows programmatically.

### Features
- **MCP-compatible endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Single URL used across clients; authentication is handled when adding the server to each application.

- **Wishpond platform integration**  
  - Access to Wishpond’s marketing capabilities, including:  
    - Campaign creation and management  
    - Landing page creation and management  
    - Lead flow management and related lead-generation workflows

- **Client-agnostic setup**  
  - Designed to be added to various MCP-compatible chat clients and applications.  
  - Uses a shared configuration flow: connect a Wishpond account, select a client, and then attach the MCP server.

- **Centralized configuration**  
  - Configuration is managed via a dedicated configuration page on Pipedream.  
  - Account checking and connection handled through the Pipedream interface.

- **Tooling exposure (via MCP tools)**  
  - The server exposes “tools” (actions and operations) that can be loaded and called by MCP clients for Wishpond operations.  
  - Tools are discoverable dynamically by the MCP client (shown as “Loading actions…” / “Loading available tools…” in the UI).

### Integration & Usage
- Add the MCP server URL (`https://mcp.pipedream.net/v2`) to a supported chat client or application.  
- Authenticate with your Wishpond account through Pipedream.  
- Once connected, your MCP client can call Wishpond-related tools to work with campaigns, landing pages, and lead flows.

### Pricing
- No pricing information is provided in the available content for the Wishpond MCP Server or its usage via Pipedream.
