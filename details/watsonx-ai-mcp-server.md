# Watsonx AI MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** IBM

An MCP server that connects to IBM watsonx.ai, exposing its enterprise AI and data platform capabilities within MCP-compatible tools and workflows.

---

## Features

- **Watsonx.ai integration**  
  - Connects directly to IBM watsonx.ai, IBM’s enterprise AI and data platform.  
  - Makes watsonx.ai capabilities available inside MCP-enabled applications and developer tools.

- **Standard MCP server endpoint**  
  - Provides a static MCP server URL for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Same endpoint can be reused across different chat or MCP clients.

- **Client-agnostic configuration**  
  - Designed to be added to multiple chat or MCP clients.  
  - Per-client setup guidance available via the configuration flow (select your client to see specific steps).

- **Authentication flow**  
  - Authentication occurs when adding the server to your application, rather than being tied to the static URL itself.

- **Configuration support via UI**  
  - “Configure WatsonX AI” flow to connect your account and select a client.  
  - Status feedback such as “Checking your account…” during setup.

- **Tool exposure**  
  - Exposes watsonx.ai tools / actions to MCP clients (shown as “Available tools,” “Loading actions…,” “Loading available tools…” in the interface).  
  - Intended to make watsonx.ai AI and data operations callable as tools within workflows.

---

## Typical Use Cases

- Integrate IBM watsonx.ai models and data operations into MCP-based chat or coding assistants.  
- Use watsonx.ai as the AI backend for enterprise workflows running through MCP-compatible tools.  
- Centralize access to watsonx.ai via a single server URL across multiple clients.

---

## Pricing

No pricing information is provided in the available content. Users will typically need an appropriate IBM watsonx.ai account/plan and any relevant Pipedream or platform usage terms.