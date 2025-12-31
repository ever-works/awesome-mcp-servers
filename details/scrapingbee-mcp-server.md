# ScrapingBee MCP Server

## Overview
ScrapingBee MCP Server integrates the ScrapingBee web scraping API into the Model Context Protocol (MCP), allowing MCP-based agents and chat clients to perform web scraping using an API that manages headless browsers and rotating proxies.

- **Type:** MCP server / web scraping integration
- **Category:** Content extraction & summarization MCP servers
- **Provider / Brand:** ScrapingBee (via Pipedream Connect)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP Integration**
  - Exposes ScrapingBee capabilities as an MCP server endpoint for MCP-compatible clients.
  - Uses a single static MCP server URL that works across supported clients.
  - Authentication is handled when adding the server within the client/application.

- **Web Scraping via API**
  - Provides access to ScrapingBee’s web scraping API.
  - Designed for programmatic scraping from MCP-based agents and tools.

- **Headless Browser Management**
  - API manages headless browsers, so clients do not need to run or maintain browser instances themselves.

- **Rotating Proxies**
  - API automatically manages rotating proxies to help reduce blocking and rate-limiting issues during scraping.

- **Client Setup & Configuration**
  - A single static server URL (`https://mcp.pipedream.net/v2`) is used for all clients.
  - Documentation is available via a configuration page for adding the server to different chat clients.

## Pricing
No pricing information is provided in the available content.

## Links
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Configuration / Getting Started:** `/configuration` (on Pipedream)
- **Provider:** https://pipedream.com/connect
- **Terms:** https://pipedream.com/terms
- **Privacy Policy:** https://pipedream.com/privacy