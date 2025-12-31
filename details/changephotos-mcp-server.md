# change.photos MCP Server

**Category:** Media Processing MCP Servers  
**Brand:** change.photos  
**Slug:** `changephotos-mcp-server`

An MCP server that exposes the change.photos photo processing API—enabling MCP clients to resize, compress, sharpen, blur, and otherwise transform images at scale.

---

## Features

- **Photo processing API integration**  
  - Direct access to the change.photos API from any compatible MCP client.  
  - Designed for web and app development use cases.

- **Single static MCP server URL**  
  - MCP endpoint: `https://mcp.pipedream.net/v2`  
  - Same URL works across all supported MCP clients; authentication is handled when adding the server to the application.

- **Image transformation action**  
  - `Transform Image` action exposed as an MCP tool.  
  - Applies various effects and optimizations to images, including:  
    - Resize  
    - Compress  
    - Sharpen  
    - Blur  
    - Additional image transformations (per change.photos API capabilities).

- **MCP client compatibility**  
  - Can be added to multiple chat / MCP clients (e.g., ChatGPT via OpenAI).  
  - Step-by-step configuration available via the Pipedream MCP configuration page.

- **Account-based configuration**  
  - Connect a change.photos account through Pipedream.  
  - Manage connected accounts and authentication for use within MCP clients.

---

## Usage

1. **Connect account:** Sign in via Pipedream to connect a change.photos account.  
2. **Copy server URL:** Use `https://mcp.pipedream.net/v2` as the MCP server endpoint.  
3. **Add to client:** Add the server in your MCP-compatible client (e.g., ChatGPT) following the provided guide.  
4. **Call tools:** Use the `Transform Image` tool to apply resizing, compression, sharpening, blurring, and other transformations at scale.

---

## Pricing

No pricing information is provided in the available content. Refer to the main change.photos or Pipedream sites for any plan or usage cost details.
