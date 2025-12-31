# Platform.ly MCP Server

## Overview
The Platform.ly MCP Server connects Platform.ly’s marketing automation and CRM platform to Model Context Protocol (MCP) clients, allowing AI-powered applications to interact with Platform.ly for automated marketing and CRM workflows.

- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Integrates:** Platform.ly (marketing automation & CRM) ↔ MCP-compatible clients
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL (`https://mcp.pipedream.net/v2`) usable across clients.  
  - Designed to be added to various MCP-capable chat or AI applications.

- **Platform.ly account connectivity**  
  - Connects to a Platform.ly account from within the MCP client.  
  - Supports selection of a specific Platform.ly client/account context after connection.

- **Authentication at client level**  
  - Uses a single, static server URL for all users; authentication occurs when adding the server to each application, so individual users authenticate separately.

- **Tooling exposure to MCP clients**  
  - Exposes "tools" (actions) from Platform.ly to MCP clients, enabling automated use of Platform.ly capabilities via MCP.  
  - Tools are dynamically loaded (“Loading actions…”, “Loading available tools…”) based on the connected account.

- **Marketing automation & CRM workflow enablement**  
  - Designed to bridge Platform.ly’s CRM and marketing automation features (e.g., campaigns, contact management) into MCP environments so AI agents can trigger or manage workflows.

- **Multi-client setup guidance**  
  - Supports configuration with different MCP-capable chat clients, with per-client instructions referenced from the configuration flow.

- **Central configuration documentation**  
  - Linked configuration page for full setup instructions within Pipedream’s environment.

## Pricing
Pricing details are not provided in the available content.