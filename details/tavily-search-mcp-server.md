# Tavily Search MCP Server

## Overview
The Tavily Search MCP Server is an open-source Model Context Protocol (MCP) server that connects Tavily’s search and news APIs to LLM tools. It is designed to provide controlled web search capabilities, including fine-grained control over which sites are included or excluded from results.

Repository: <https://github.com/RamXX/mcp-tavily>  
License: MIT  
Status: Archived (read-only)

## Features
- **MCP server for Tavily APIs**  
  - Exposes Tavily’s search and news functionality through the Model Context Protocol so it can be used by MCP-compatible LLM clients.

- **Controlled web search**  
  - Supports explicit inclusion and exclusion of websites/domains to constrain where results are sourced from.

- **LLM tool integration**  
  - Designed to be invoked as tools/functions by LLM-based applications that support MCP.

- **Open-source implementation**  
  - Source code available on GitHub.
  - Licensed under the MIT license.

- **Containerization and tooling**  
  - `Dockerfile` included for container-based deployment.  
  - `Makefile` present for common development or build tasks.

- **Tested codebase**  
  - `tests` directory included for automated testing.

## Technical Details
- **Tech stack**: Python (project metadata via `pyproject.toml`, `requirements.txt`).
- **Code layout**: Core server implementation under `src/mcp_server_tavily`.
- **Automation & CI**: GitHub workflows under `.github/workflows`.
- **Project type**: MCP server specifically tailored to Tavily’s search and news APIs.

## Pricing
- The MCP server code in this repository is **MIT-licensed open source**; no usage fee is specified for the software itself.
- Pricing or limits for Tavily’s underlying APIs are **not specified in this repository** and must be obtained from Tavily’s official documentation or website.