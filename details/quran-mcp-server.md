# Quran MCP Server

**Brand:** qurancom  
**Category:** Data Access & Integration – MCP Servers  
**Source:** <https://github.com/djalal/quran-mcp-server>

## Overview
Quran MCP Server is a Model Context Protocol (MCP) server that integrates with the official Quran.com REST API v4. It enables search and retrieval of Quranic text and related metadata for use by MCP‑compatible tools and agents.

## Features
- **Quran.com API v4 integration**  
  - Uses the official Quran.com REST API v4 corpus.  
  - Access to Quranic text and associated metadata via HTTP.

- **Verse search**  
  - Search verses programmatically through the Quran.com API.  
  - Designed to be called within MCP‑aware environments.

- **Text retrieval**  
  - Retrieve Quranic verses on demand.  
  - Works as a backend data provider for MCP tools.

- **Translations access**  
  - Integrates Quran.com translation resources exposed via API v4.  
  - Allows MCP clients to request translated verse content.

- **Tafsir access**  
  - Exposes tafsir (exegesis) resources made available by Quran.com via its API.  
  - Useful for contextual and explanatory information around verses.

- **MCP server implementation**  
  - Implemented as an MCP-compatible server so LLM tools can call structured tools/endpoints.  
  - Organized `src` and `tests` directories, with TypeScript configuration (`tsconfig.json`).

- **Containerization support**  
  - `Dockerfile` included for building and running the MCP server in containers.  
  - `.dockerignore` provided to optimize Docker builds.

- **Node.js / TypeScript project setup**  
  - `package.json` and `package-lock.json` for dependency and script management.  
  - Jest configuration (`jest.config.js`) for automated testing.

- **Configuration artifacts**  
  - `v4.json` (referenced in the repo) likely used for API or schema configuration related to Quran.com v4.

- **Open-source licensing**  
  - Licensed under the MIT License.

## Pricing
- Not applicable – this is an open-source project released under the MIT License; no pricing plans are listed.