# ZeroTier MCP Server

**Category:** Cloud & DevOps – MCP Servers  
**Brand:** ZeroTier

An MCP server integration for ZeroTier’s virtual networking platform, enabling MCP-compatible tools and chat-based clients to manage and interact with software-defined networks that connect devices, cloud VMs, and applications.

---

## Features

- **MCP-compatible ZeroTier integration**  
  - Exposes ZeroTier’s virtual networking capabilities through the Model Context Protocol (MCP), so MCP-aware tools and chat clients can work with software-defined networks.

- **Virtual network management**  
  - Designed to interact with ZeroTier networks that connect devices, cloud VMs, and applications as if they are in a single unified cloud region.

- **Static MCP server endpoint**  
  - Single shared MCP server URL for all clients:  
    `https://mcp.pipedream.net/v2`  
  - Simplifies configuration across different applications and environments.

- **Authentication at client setup**  
  - Authentication occurs when adding the server to your MCP-compatible application, allowing secure access tied to each client.

- **Client-agnostic setup**  
  - Can be added to multiple types of chat or MCP clients using the same server URL.  
  - Additional configuration details are available via the referenced configuration documentation (per-client setup flows).

- **Hosted by Pipedream Connect**  
  - The MCP server is provided as a hosted service via Pipedream’s Connect platform, so you don’t need to deploy or manage the MCP server infrastructure yourself.

---

## MCP Server URL

```text
https://mcp.pipedream.net/v2
```

Use this URL when adding the ZeroTier MCP Server to your MCP-compatible client or application.

---

## Pricing

The provided content does not list any pricing or plans for the ZeroTier MCP Server. Pricing details, if available, would need to be obtained from the linked Pipedream or ZeroTier resources.