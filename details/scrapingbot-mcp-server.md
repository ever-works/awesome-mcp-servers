# ScrapingBot MCP Server

**Category:** Content Extraction & Summarization MCP Servers  
**Brand:** ScrapingBot  
**Slug:** `scrapingbot-mcp-server`

A Pipedream-hosted MCP (Model Context Protocol) server that exposes ScrapingBot’s web scraping APIs, enabling retrieval of HTML content from web pages without being blocked.

---

## Features

- **MCP Server for ScrapingBot**
  - Provides a Model Context Protocol endpoint wrapping ScrapingBot’s web scraping APIs.
  - Designed to be used from MCP-compatible chat or AI clients.

- **Static MCP Server URL**
  - Single static endpoint for all clients:  
    `https://mcp.pipedream.net/v2`
  - Same URL works across different tools and applications.

- **Authentication at Client Setup**
  - Authentication is handled when adding the server to your application / client.
  - Keeps the server URL static while credentials are managed per client.

- **HTML Content Extraction**
  - Access to APIs optimized for extracting raw HTML content from target web pages.
  - Intended to work on sites that commonly block basic scrapers.

- **Anti‑Blocking / Proxy Support**
  - Built on ScrapingBot infrastructure focused on avoiding IP blocks and rate limits.
  - Uses proxy and anti-bot techniques (as implied by ScrapingBot’s purpose) to reduce blocking.

- **Integration with Pipedream Connect**
  - Hosted and powered by Pipedream Connect.
  - Benefits from Pipedream’s infrastructure, terms, and privacy controls.

- **Multi‑Client Compatibility**
  - Can be added to various chat or AI clients that support MCP.
  - Configuration details available via the Pipedream MCP configuration documentation.

---

## Usage

- Use the static MCP URL `https://mcp.pipedream.net/v2` in your MCP-compatible client.
- Configure authentication when adding the server in your client or application.
- Use available MCP tools (as exposed by the client) to request HTML content from target URLs.

---

## Pricing

- No pricing information is provided in the available content.

---

## Links

- MCP Server / App Page: https://mcp.pipedream.com/app/scrapingbot
- Pipedream Connect: https://pipedream.com/connect
- Terms: https://pipedream.com/terms
- Privacy Policy: https://pipedream.com/privacy