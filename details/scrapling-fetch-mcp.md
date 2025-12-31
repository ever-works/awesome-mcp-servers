# scrapling-fetch MCP

## Overview
scrapling-fetch MCP is an MCP server that uses the Scrapling service to retrieve text content (HTML or Markdown) from websites that implement bot detection and anti-automation measures, allowing AI assistants to access content closer to what a human would see in a browser.

- **Type:** MCP server (for AI assistants / LLM tools)
- **Category:** content-extraction-summarization-mcp-servers
- **Source:** Open source (Apache-2.0 license)
- **Code repository:** https://github.com/cyberchitta/scrapling-fetch-mcp

## Features
- **Access to bot-protected sites**
  - Fetches content from websites with bot detection and anti-automation / anti-scraping mechanisms.
  - Bridges the gap between browser-visible content and what typical HTTP clients or basic scrapers can access.

- **Content formats**
  - Retrieves page content as **HTML**.
  - Retrieves page content as **Markdown**, enabling easier downstream processing and summarization.

- **MCP integration**
  - Exposes functionality as an **MCP server** so AI assistants and tools within the Model Context Protocol ecosystem can call it.
  - Designed specifically for “low-volume” retrieval to support tasks like documentation lookup and reference gathering inside AI workflows.

- **Documentation-focused retrieval**
  - Optimized for fetching documentation and reference pages that may be partially or fully blocked by bot protection when accessed via standard programmatic methods.

- **Scrapling-based backend**
  - Uses **Scrapling** as the underlying service for robust, browser-like content retrieval from protected sites.

- **Open-source project**
  - Distributed under the **Apache-2.0** license, allowing modification and integration into other systems.

## Pricing
No pricing information is provided in the available content for the `scrapling-fetch MCP` project itself. (It is an open-source repository under Apache-2.0; any pricing for the underlying Scrapling service, if applicable, is not described in the provided content.)
