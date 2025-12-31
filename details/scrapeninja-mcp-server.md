# ScrapeNinja MCP Server

An MCP server integration for ScrapeNinja that lets MCP-compatible clients extract web data at scale via the ScrapeNinja scraping service, hosted by Pipedream.

---

## Features

- **MCP-compatible server**  
  - Exposes ScrapeNinja’s web scraping capabilities as an MCP server endpoint.  
  - Can be added to any MCP-enabled chat or developer client.

- **Static MCP server URL**  
  - Single stable endpoint for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Same URL works across different MCP clients; authentication is handled when adding the server to your app.

- **Account-based configuration**  
  - Connect your ScrapeNinja / Pipedream account to configure access.  
  - Once connected, you can select a client and start using ScrapeNinja via MCP.

- **Tool exposure for clients**  
  - Designed to expose ScrapeNinja actions as MCP tools (e.g., web scraping / data extraction operations).  
  - Tools are discovered dynamically by compatible MCP clients ("Loading actions…", "Loading available tools…").

- **Developer-focused setup**  
  - Targeted at developers integrating web scraping into MCP-based workflows or chat clients.  
  - Documentation available via a central configuration page (Pipedream Configuration page).

---

## Integration & Usage

- Add the server URL `https://mcp.pipedream.net/v2` to your MCP-compatible application.  
- Authenticate when prompted by your client to connect your account.  
- Use the exposed MCP tools to run ScrapeNinja-powered web data extraction from within your client.

---

## Pricing

- Not specified in the provided content. Refer to the Pipedream / ScrapeNinja pages for detailed pricing information.