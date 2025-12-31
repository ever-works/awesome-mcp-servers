# kiwiHR MCP Server

**Description**

The kiwiHR MCP Server (Tellent HR – Manage, formerly kiwiHR) exposes workforce and HR management capabilities via the Model Context Protocol (MCP), allowing chat-based clients and tools to integrate with Tellent’s HR software for streamlined workforce management.

**MCP Server URL**

```text
https://mcp.pipedream.net/v2
```

This is a static URL used by all MCP-compatible clients; authentication is handled when you add the server to your application.

---

## Features

- **MCP-based access to Tellent HR – Manage (formerly kiwiHR)**
  - Connects Tellent’s HR / workforce management system to MCP-compatible chat clients and applications.
- **Central MCP endpoint**
  - Uses a single, static MCP server URL (`https://mcp.pipedream.net/v2`) for all clients.
- **Client-agnostic integration**
  - Designed to work with multiple chat clients that support MCP.
- **Authentication at connection time**
  - You authenticate when adding the server to your application (per-client auth flow).
- **Configuration guidance available**
  - A dedicated configuration page (via Pipedream) provides instructions for adding and using the server in different clients.

*(The underlying HR features—such as specific workforce or HR management operations—are provided by Tellent HR – Manage / kiwiHR, but are not detailed in the provided content.)*

---

## Pricing

No pricing information is provided in the available content.