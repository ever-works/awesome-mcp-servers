# AdRoll MCP Server

**Category:** Business & Commerce – MCP Servers  
**Brand:** AdRoll  
**Source:** https://mcp.pipedream.com/app/adroll

## Overview
The AdRoll MCP Server is a Model Context Protocol (MCP) connector that exposes AdRoll’s online advertising and retargeting capabilities to MCP-compatible tools via Pipedream. It allows applications (such as chat clients) to interact with AdRoll programmatically through a shared MCP server endpoint.

## Features
- **MCP-compatible connector for AdRoll**  
  - Provides a standardized MCP interface to AdRoll’s advertising and retargeting capabilities.
- **Static MCP server URL**  
  - Uses a single static endpoint for all clients:  
    - `https://mcp.pipedream.net/v2`
  - The same URL can be reused across different applications and clients.
- **Account connection and configuration**  
  - Connect an AdRoll account within the Pipedream-hosted interface.  
  - Select the desired client (AdRoll account/client entity) after connection.
- **Authentication at application level**  
  - Authentication is handled when adding the MCP server to the consuming application, rather than by changing the server URL.
- **Integration with chat clients**  
  - Can be added as an MCP server to supported chat clients to enable AdRoll-related tools and actions directly from those clients.
- **Tool exposure via MCP**  
  - Designed to expose AdRoll actions and tools (e.g., for advertising and marketing workflows) through the MCP protocol so that compatible apps can load and call them.  
  - Tools appear as “available tools” within MCP-enabled clients once the server is configured.
- **Central configuration reference**  
  - Has a full configuration page (linked from the app) describing how to integrate and configure the MCP server across clients.

## Technical Details
- **MCP server endpoint:** `https://mcp.pipedream.net/v2`  
- **Hosting:** Provided by Pipedream as a managed MCP server.  
- **Usage pattern:**
  1. Connect AdRoll account in the Pipedream UI.  
  2. Select the relevant client/account.  
  3. Copy the MCP server URL.  
  4. Add the server URL to the MCP-compatible app (e.g., chat client) and authenticate there.  
  5. Use exposed tools/actions for AdRoll-related tasks.

## Pricing
No pricing details are provided in the available content.