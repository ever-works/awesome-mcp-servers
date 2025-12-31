# Brave Search MCP Server

**Category:** Web Search MCP Servers  
**Brand:** Brave  
**License:** MIT  
**Source:** https://github.com/brave/brave-search-mcp-server

## Description
Brave Search MCP Server is a Model Context Protocol (MCP) server that integrates the Brave Search API to provide privacy-focused web search capabilities to AI tools and agents. It enables LLMs and MCP-compatible clients to perform web queries using Brave’s search infrastructure.

## Features
- **Brave Search integration** – Uses the Brave Search API as the underlying search engine.
- **Privacy-focused search** – Designed to leverage Brave’s privacy-centric search stack.
- **MCP-compliant server** – Implements the Model Context Protocol so it can be used by MCP-compatible clients and tools.
- **Web search tools for AI** – Exposes web search functionality that can be called programmatically by AI agents.
- **Configurable via repository files** – Includes configuration and metadata files such as:
  - `glama.json` for MCP/tooling metadata
  - `marketplace-revision-release.json` for release metadata
- **Containerization support** – Provides a `Dockerfile` for building a container image.
- **Docker Compose setup** – Includes `docker-compose.yml` for running the server via Docker Compose.
- **Source-organized implementation** – Core server logic contained under `src/` directory.
- **Development tooling configuration** – Includes `.prettierrc` and `.prettierignore` for code formatting, and `.gitignore` for repository hygiene.

## Technical Details
- **Primary language:** (not explicitly stated in snippet; source is under `src/`)  
- **Repository stats (approximate, from snapshot):** ~400 commits, 400+ stars, 90+ forks.

## Pricing
- Not specified in the provided content. The project is open source under the MIT license; any API usage costs (e.g., Brave Search API) are not detailed in the snippet and would need to be checked in Brave’s API documentation.