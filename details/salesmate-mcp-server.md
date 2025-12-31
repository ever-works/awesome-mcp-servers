# Salesmate MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Salesmate  
**Slug:** `salesmate-mcp-server`

## Overview
Salesmate MCP Server is an MCP (Model Context Protocol) server integration that connects MCP-compatible clients to the Salesmate CRM and unified customer platform. It enables chat-based or MCP-aware applications to interact with Salesmate data and workflows through a standardized MCP endpoint.

## Features
- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Works across MCP clients; authentication is handled when adding the server to the client/app.

- **Salesmate CRM integration**  
  - Connects to a Salesmate account as part of configuration.  
  - Designed to expose Salesmate’s CRM and unified customer platform capabilities to MCP clients (e.g., for sales, CRM, and customer engagement scenarios).

- **Client configuration workflow**  
  - Connect a Salesmate account via Pipedream.  
  - Select a client (MCP-compatible chat or application) after account connection.  
  - Use the provided MCP URL inside the client configuration to enable interaction with Salesmate.

- **Tooling exposure (via MCP tools/actions)**  
  - The server exposes its capabilities to MCP clients as "available tools" / "actions" (the specific tools are loaded dynamically and not listed in the source content).  
  - Tools are intended for CRM-related operations (e.g., working with sales and customer engagement data), though the exact operations are not enumerated in the provided content.

## Integration & Usage
- Add the static MCP server URL to a compatible chat client or MCP application.  
- Authenticate with Salesmate during the add-server flow.  
- Use the MCP client’s interface to call the Salesmate tools/actions that the server makes available.

## Pricing
The provided content does not specify any pricing or plans for the Salesmate MCP Server or its usage via Pipedream.