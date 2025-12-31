# ZenRows MCP Server

An MCP-compatible server that connects agents and tools to the ZenRows web scraping API and rotating proxy infrastructure for extracting structured data from websites at scale.

## Overview
- **Type:** MCP server / integration
- **Provider:** ZenRows (via Pipedream Connect)
- **Category:** Content extraction & summarization MCP servers
- **Primary use case:** Programmatic web scraping with anti-blocking measures through an MCP endpoint

## MCP Server Endpoint
- **Universal MCP server URL:** `https://mcp.pipedream.net/v2`
- This static URL is used for all MCP-compatible clients.
- Authentication is performed when adding the server to the target application or client.

## Features
- **Web scraping API integration**
  - Connects MCP-compatible agents directly to the ZenRows web scraping API.
  - Designed to extract structured data from arbitrary websites.

- **Rotating proxy services**
  - Uses ZenRows’ rotating proxies to distribute requests across many IPs.
  - Helps reduce blocking and throttling when scraping at scale.

- **Anti-blocking measures**
  - Built to support “undetected” scraping techniques (e.g., rotation, evasion strategies implemented by ZenRows API).
  - Intended for large-scale data collection with lower risk of being blocked.

- **MCP compatibility**
  - Exposes ZenRows capabilities via the Model Context Protocol so agents and tools can:
    - Add the server as a context/tooling provider.
    - Call scraping / proxy-enabled operations through standardized MCP flows.

- **Single static server URL**
  - Uses a single, static base URL (`https://mcp.pipedream.net/v2`) for all clients.
  - Simplifies configuration across multiple chat clients and applications.

- **App/client integration guidance**
  - Designed to be added to various chat clients and MCP-compatible apps using the same server URL.
  - Configuration details are available via the referenced configuration page (outside this summary).

## Pricing
- Not specified in the provided content.

## Tags
- Web scraping
- API integration
- Proxies
