# SwagUp MCP Server

## Overview
SwagUp MCP Server is a Model Context Protocol (MCP) server that integrates SwagUp’s swag management and fulfillment capabilities into MCP-compatible clients. It allows applications (such as chat-based clients) to connect to SwagUp via a static MCP server URL and then authenticate per client/application.

- **Category:** Business & Commerce – MCP Servers  
- **Use cases:** Branded swag management, automated swag distribution, gifting, marketing and fulfillment workflows

## Features
- **MCP-compatible server endpoint**  
  - Uses a static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL works for all clients; authentication is handled when the server is added to each application.

- **SwagUp integration**  
  - Connects an MCP client to a SwagUp account.  
  - Supports creating, automating, and distributing branded swag through SwagUp’s platform (as exposed via the server’s tools/actions).

- **Per-client configuration**  
  - After connecting a SwagUp account, users select the client they are using to configure the MCP server for that specific environment.  
  - Configuration guidance is provided per chat client or via a dedicated configuration page.

- **Tool / action exposure**  
  - Exposes SwagUp-related actions as MCP tools that can be invoked from compatible clients.  
  - Tools are dynamically loaded by the MCP client (listed as “Available tools” / “Loading actions…” in the interface).

- **Account-based authentication**  
  - Requires connecting a SwagUp account before using the tools.  
  - Authentication occurs when adding the server to the application, not when accessing the static URL itself.

## Configuration
- **Server URL:** `https://mcp.pipedream.net/v2`  
- **Setup steps (high level):**  
  1. Connect a SwagUp account via the Pipedream-hosted configuration UI.  
  2. Copy the static MCP server URL.  
  3. Add the MCP server to the desired app or chat client.  
  4. Follow client-specific instructions (or the full configuration page) to complete setup and authenticate.

## Pricing
- Not specified in the provided content.
