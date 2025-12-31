# Clockify MCP Server

**Category:** Project Management MCP Servers  
**Brand:** Clockify  
**Type:** MCP Server integration

An MCP Server integration that exposes Clockify’s time tracking features and data through the Model Context Protocol (MCP), enabling time tracking workflows inside compatible MCP clients.

---

## Features

- **MCP-based integration with Clockify**  
  - Provides access to Clockify’s time tracking functionality and data through the MCP standard.  
  - Designed to be added as an MCP server in compatible chat or AI applications.

- **Static MCP server endpoint**  
  - Uses a single, static base URL for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Same endpoint works across different MCP-compatible applications.

- **Account connection & configuration**  
  - Connect a Clockify account via the Pipedream configuration flow.  
  - Allows selection of a specific client/workspace during setup.  
  - Authentication is handled when adding the server to the application (not embedded in the URL).

- **Tooling / actions exposure**  
  - Exposes Clockify-related tools/actions over MCP (e.g., for time tracking and data access).  
  - Tools are dynamically loaded and made available to the client (listed as “Available tools” in the interface).

- **Client-agnostic usage**  
  - Can be added to various MCP-compatible chat clients.  
  - Documentation available via a general configuration page for different client types.

---

## Setup & Integration

1. Connect your Clockify account in the Pipedream UI.
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
3. Add the server URL to your MCP-compatible application.  
4. Authenticate when prompted by the client and start using the exposed Clockify tools.

---

## Pricing

- Described alongside Clockify as “100% Free Time Tracking Software.”  
- No separate pricing details for the MCP server are provided in the referenced content.