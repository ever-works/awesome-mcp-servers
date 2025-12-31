# open-webSearch

**Category:** Web Search MCP Servers  
**Repository:** https://github.com/Aas-ee/open-webSearch  
**License:** Apache-2.0  
**Type:** Open-source MCP-compatible web search server

## Overview
open-webSearch is an MCP-compatible web search server that performs web searches across multiple free search engines without requiring API keys. It is designed to be self-hosted and integrates with the Model Context Protocol to provide search capabilities to AI agents and tools.

## Features
- **MCP-compatible server**
  - Implements a web search server compatible with the Model Context Protocol (MCP) for integration with AI tools and agents.

- **No API keys required**
  - Uses publicly accessible search interfaces, removing the need to manage or pay for search API keys.

- **Multi-engine search support**
  - Aggregates or queries results from multiple search engines:
    - Bing
    - Baidu
    - DuckDuckGo
    - Brave
    - Exa
    - GitHub search
    - Juejin
    - CSDN

- **Open-source implementation**
  - Source available under the Apache-2.0 license.
  - Forked from `pskill9/web-search`, with additional engines and MCP-focused enhancements.

- **Containerized deployment**
  - `Dockerfile` included for containerized builds.
  - `docker-compose.yml` provided for orchestrated local or server deployment.

- **Node.js-based service**
  - `package.json` and `package-lock.json` define dependencies and scripts for installing and running the server.

- **CI/CD workflow definitions**
  - GitHub Actions workflows present under `.github/workflows` for automated build/test processes (details defined in the repo’s workflow files).

- **Multi-language documentation**
  - README available in English (`README.md`).
  - Chinese documentation available (`README-zh.md`).

## Pricing
- **Cost:** Free, open-source (Apache-2.0 license). No usage-based pricing is defined in the repository; operation costs are limited to your own hosting and infrastructure.
