# Metatext.AI Inference API MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** Metatext.AI  
**Slug:** `metatextai-inference-api-mcp-server`

Metatext.AI Inference API MCP Server exposes Metatext.AI’s inference capabilities via the Model Context Protocol (MCP), enabling MCP-compatible clients to interact with custom AI models for reading and writing tasks through a standardized server endpoint.

---

## Features

- **MCP-compatible server**  
  - Implements an MCP Server interface for use with MCP-capable chat and development clients.

- **Access to Metatext.AI Inference API**  
  - Connects MCP clients to Metatext.AI’s inference endpoints for AI-powered reading and writing operations.

- **Static MCP server URL**  
  - Single shared endpoint for all clients:  
    - `https://mcp.pipedream.net/v2`
  - URL is the same regardless of client; authentication is handled when adding the server to an application.

- **Client-agnostic integration**  
  - Works with multiple MCP-enabled chat clients and tools.  
  - Can be added to different applications using the same server URL.

- **Configuration guidance (external)**  
  - Full configuration details available via a dedicated configuration page (outside this summary) for setting up the MCP server in various clients.

- **Hosted and delivered via Pipedream Connect**  
  - The MCP server is provided and hosted by Pipedream’s Connect platform, which handles routing to the Metatext.AI Inference API.

---

## Usage

- Use the static MCP endpoint `https://mcp.pipedream.net/v2` when configuring the server in your MCP-compatible client.
- Authenticate during the server addition process according to your client’s MCP configuration flow.

---

## Pricing

- Not specified in the provided content.