# Survey2Connect MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Survey2Connect  
**Slug:** `survey2connect-mcp-server`

Survey2Connect MCP Server is an integration that exposes Survey2Connect’s customer experience and survey capabilities to AI tools via the Model Context Protocol (MCP). It is hosted by Pipedream and accessed through a static MCP server URL.

---

## Features

- **MCP Integration for Survey2Connect**  
  - Provides a Model Context Protocol (MCP) server that connects AI clients to Survey2Connect.  
  - Designed to expose Survey2Connect’s customer experience, survey, and analytics capabilities to MCP-compatible tools.

- **Static MCP Server Endpoint**  
  - Single static URL for all clients: `https://mcp.pipedream.net/v2`.  
  - Works across different chat or AI clients that support MCP.  
  - Authentication occurs when adding/configuring the server within the client, rather than via different URLs.

- **Account Connection Flow**  
  - Users connect their Survey2Connect account within the Pipedream-based interface.  
  - After connection, users select a client (e.g., chat client) to start using Survey2Connect tools.  
  - Includes basic status checks like “Checking your account…” during setup.

- **Client-Agnostic Setup**  
  - Supports adding the server to various chat or AI clients.  
  - Provides client-specific setup guidance (via “Select your chat client to learn how to get started”).

- **Configuration Documentation**  
  - Linked “Configuration” page with more detailed setup instructions for MCP and Survey2Connect integration.

- **Tooling Exposure (Actions)**  
  - The MCP server exposes “available tools” (actions) from Survey2Connect to the AI client (e.g., for surveys, customer experience operations, analytics).  
  - Tools are dynamically loaded (“Loading actions…”, “Loading available tools…”), indicating the set of operations available through the MCP interface.

---

## Pricing

No pricing information is provided in the available content. Users should refer to Pipedream or Survey2Connect directly for plan and pricing details.

---

## Technical Details

- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Protocol:** Model Context Protocol (MCP)  
- **Host / Provider:** Pipedream (integration layer for Survey2Connect)

---

## Tags

- Survey  
- Customer Experience  
- Analytics