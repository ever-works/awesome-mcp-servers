# News API MCP Server

An MCP server integration for NewsAPI.org that enables MCP-compatible applications to search and retrieve news and blog articles from across the web.

---

## Overview
- **Type:** MCP server / web search integration
- **Provider:** Pipedream
- **Category:** Web search MCP servers
- **Primary function:** Programmatic search and retrieval of news and blog articles via NewsAPI.org within MCP-compatible clients (e.g., ChatGPT).

---

## Features

### MCP Server Endpoint
- **Static MCP server URL:** `https://mcp.pipedream.net/v2`
- Single, static URL that works for all compatible clients.
- Authentication occurs when adding the server to an application.

### News & Blog Search Capabilities
- Integrates with **NewsAPI.org** to access news and blog content from across the web.
- Supports news-oriented use cases such as:
  - Monitoring breaking news
  - Searching historical articles
  - Working with both large and small news sources and blogs

### Available Tools (Actions)

1. **Search Top Headlines**
   - Retrieves live top and breaking headlines.
   - Supports filtering by:
     - Category
     - Single source
     - Multiple sources
     - Keywords
   - Intended for up-to-date headline and breaking news queries.

2. **Search Everything**
   - Searches through millions of articles.
   - Sources include over **150,000** large and small news outlets and blogs.
   - Designed for broader, historical, or deep content searches beyond just top headlines.

### Client Integration
- Designed to be added as an MCP server to compatible chat clients.
- Example client:
  - **ChatGPT (OpenAI)** – usage instructions available via a dedicated guide.
- Additional configuration details available on the Pipedream MCP configuration page.

---

## Configuration & Access
- Requires a News API account connection.
- Users sign in via the Pipedream MCP interface to connect News API and manage accounts.
- After sign-in, the same MCP server URL can be used across supported clients.

---

## Pricing
- No explicit pricing information is provided in the available content.
- Any costs are likely governed by NewsAPI.org and/or Pipedream plans, but details are not specified in the provided text.