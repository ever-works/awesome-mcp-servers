# Aimtell MCP Server

**Description**

The Aimtell MCP Server is a Model Context Protocol (MCP) server that exposes Aimtell’s web push notification capabilities to MCP-compatible applications. It enables applications to interact with Aimtell for acquiring, engaging, monetizing, and retaining website visitors and subscribers via push notifications.

**Category**

- Messaging MCP Servers

**Features**

- MCP endpoint for Aimtell: static server URL `https://mcp.pipedream.net/v2` for all clients.
- Compatible with multiple MCP-enabled chat or agent clients (added as an external MCP server).
- Authentication performed when adding/configuring the server in the client application.
- Provides access to Aimtell web push notification features focused on:
  - Acquiring website visitors as subscribers.
  - Engaging subscribers via push notifications.
  - Monetizing audiences through notification-driven campaigns.
  - Retaining visitors and subscribers.
- Central configuration via a “Configure Aimtell” flow where users connect their Aimtell account and select the appropriate client.
- Tools / actions are exposed as MCP tools within the client (listed as “Available tools” once loaded).

**Integration Details**

- MCP Server URL: `https://mcp.pipedream.net/v2`
- Server is static and reused across clients; client-side configuration determines which Aimtell account is used.

**Pricing**

- Not specified in the provided content.