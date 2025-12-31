# brightdata-mcp

**Category:** content-extraction-summarization-mcp-servers  
**Brand:** Bright Data  
**License:** MIT  
**Source:** https://github.com/brightdata/brightdata-mcp

## Description
brightdata-mcp is a Model Context Protocol (MCP) server by Bright Data that provides an all‑in‑one interface for AI assistants to discover, extract, and interact with content across the public web. It is designed to give automated agents structured, programmatic access to web data through a unified MCP-compatible API.

## Features
- **Model Context Protocol (MCP) server**
  - Implements an MCP-compatible server for integration with MCP-aware AI assistants and tooling.
  - Exposes tools and resources in a standardized way for automated agents.

- **Unified public web access**
  - Provides a single interface to access and interact with content across the public internet.
  - Designed for automated web tasks such as browsing, extraction, and interaction.

- **Web discovery and navigation**
  - Allows agents to discover relevant web pages before extraction (e.g., search / discovery workflows).
  - Supports automated navigation flows via MCP tools (details defined in the repository implementation).

- **Data extraction and web scraping**
  - Focused on structured extraction of data from web pages.
  - Enables AI assistants to perform scraping-like operations through MCP requests.
  - Suitable for content extraction and summarization pipelines.

- **Interaction with web content**
  - Lets AI agents not only read but also interact with web pages (e.g., following links, loading additional content – as supported by the MCP tools defined in the repo).

- **Examples and assets**
  - `examples` directory with sample usage and configurations demonstrating how to connect and use the MCP server.
  - Assets for documentation or integration demos.

- **Containerization support**
  - `Dockerfile` included for building and running the MCP server in containerized environments.

- **Node.js / npm project setup**
  - Includes `.gitignore` and `.npmignore` for typical Node.js/package distribution workflows.
  - CHANGELOG for tracking updates and versions.

- **ARIA snapshot filtering helper**
  - `aria_snapshot_filter.js` suggests utilities for filtering or processing page snapshots, likely used to improve extraction quality or accessibility-aware processing.

## Technical details
- **Repository:** `brightdata/brightdata-mcp` on GitHub.
- **Ecosystem:** Suitable for integration with MCP-compatible AI runtimes and tools.
- **Language/stack:** Node.js-based (inferred from presence of npm-related files and typical Bright Data tooling patterns).

## Pricing
No pricing information is provided in the available content. (Open-source under the MIT license; any commercial usage of Bright Data’s broader platform would be outside the scope of this repository’s documentation.)
