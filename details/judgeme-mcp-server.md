# Judge.me MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Judge.me  
**Slug:** judgeme-mcp-server

An MCP server that connects Judge.me (Shopify product and store reviews) to MCP-compatible tools, enabling interaction with review data from within chat or other MCP-based clients.

---

## Features

- **MCP server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL works for every client; authentication occurs when adding the server to an application.

- **Judge.me account connection**  
  - Connect a Judge.me account through Pipedream’s interface.  
  - Manage configured Judge.me clients/accounts once connected.

- **Available tools (actions)**  
  1. **Reply**  
     - Create a **public reply** for a review on behalf of the shop.  
     - Public replies are shown publicly on Judge.me widgets.  
     - Implemented as an MCP tool that can be invoked from supported MCP clients.  
  2. **Private Reply**  
     - Create a **private reply** for a review on behalf of the shop.  
     - Private replies are **not** shown on widgets.  
     - Private replies can be emailed to reviewers.  

- **Client integration**  
  - Can be added to MCP-compatible chat clients such as ChatGPT (OpenAI).  
  - Additional setup details available via the Pipedream MCP configuration page.

---

## Usage

1. Sign in to Pipedream and connect your Judge.me account.  
2. Copy the MCP server URL `https://mcp.pipedream.net/v2`.  
3. Add the server to your MCP-compatible app (e.g., ChatGPT) following the relevant guide.  
4. Use the provided tools to create public or private replies to Judge.me reviews from within your client.

---

## Pricing

The provided content does not list any pricing or plans for the Judge.me MCP Server. Refer to the Pipedream or Judge.me websites for current pricing details.