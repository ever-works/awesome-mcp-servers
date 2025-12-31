# Circle MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Circle

An MCP server that connects to Circle’s community platform, enabling MCP-compatible clients (such as AI/chat tools) to manage and query Circle community spaces, members, and content via a unified endpoint.

---

## Features

- **Circle community integration**  
  - Connects directly to Circle’s community platform.  
  - Designed for creators, brands, and membership communities.

- **MCP-compatible endpoint**  
  - Provides a single static MCP server URL usable across clients:
    - `https://mcp.pipedream.net/v2`  
  - Intended to be added as a server in any MCP-capable application or chat client.

- **Account-based configuration**  
  - Users connect their Circle account.  
  - Client selection flow to configure the MCP connection per chat client.

- **Community operations (conceptual / intent)**  
  - Built to let MCP clients manage and query:  
    - Community spaces  
    - Members  
    - Community content

- **Tooling integration**  
  - Exposes “available tools” (actions) to the MCP client for interacting with Circle (loading and listing occurs dynamically within the configuration UI).

- **Hosted by Pipedream**  
  - Operated as a managed MCP server via Pipedream’s infrastructure.  
  - Uses Pipedream’s configuration and terms/privacy framework.

---

## Setup & Usage

1. Connect your Circle account in the Pipedream UI.  
2. Copy the static MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add this server URL to your MCP-compatible app or chat client.  
4. Select the specific client in the configuration flow (if applicable).  
5. Use the exposed tools to interact with Circle communities through your client.

---

## Pricing

No explicit pricing information is provided in the available content.

---

## Technical Details

- **Protocol:** Model Context Protocol (MCP).  
- **Server URL:** `https://mcp.pipedream.net/v2`  
- **Hosting:** Managed by Pipedream.
