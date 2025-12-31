# Apple Health MCP Server

**Website:** https://github.com/the-momentum/apple-health-mcp-server  
**Category:** Data Analysis & Exploration MCP Servers  
**Tags:** health, analytics, apple  
**Developer / Brand:** the-momentum

## Overview
Apple Health MCP Server is an open-source Model Context Protocol (MCP) server that connects to exported Apple Health data and exposes it as queryable health metrics and analytics. It uses DuckDB under the hood so LLMs and tools can access, query, and analyze personal health records via natural language.

## Features
- **Apple Health integration**
  - Works with exported Apple Health data.
  - Focused on personal health metrics and records.

- **MCP server implementation**
  - Implements the Model Context Protocol to serve health data to LLMs and MCP-compatible tools.
  - Designed for natural-language style querying of health records.

- **Analytics and metrics exposure**
  - Exposes health metrics for analysis (e.g., time-series queries, aggregations, and other analytics driven by DuckDB capabilities).
  - Enables building health-related insights and analyses on top of Apple Health exports.

- **DuckDB-backed storage and queries**
  - Uses DuckDB as the query engine.
  - Supports efficient analytical queries over structured health data.

- **Containerization and deployment assets**
  - Docker support via multiple Dockerfiles (`Dockerfile`, `Dockerfile.ch`, `Dockerfile.uv`).
  - `docker-compose.yml` for local orchestration.

- **Developer tooling and configuration**
  - `config` directory for server/config management.
  - `scripts` for automation and development workflows.
  - `tests` directory for automated testing.
  - `.pre-commit-config.yaml` for code quality hooks.
  - `Makefile` for common setup/build/test commands.

- **Documentation**
  - `docs` directory for project documentation.
  - `README.md` with usage and setup instructions (hosted on GitHub).

- **Open-source licensing**
  - Includes a `LICENSE` file (exact license details available in the repository).

## Pricing
- No pricing information is provided in the available content. The presence of a `LICENSE` file in the repository indicates it is open source; specific license terms are available on the GitHub page.
