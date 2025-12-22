## Oxylabs MCP

**Category:** MCP Server / Tools Directory  
**License:** MIT  
**Source:** https://github.com/oxylabs/oxylabs-mcp

### Description
Oxylabs MCP is an official Model Context Protocol (MCP) server for the Oxylabs Web API. It enables tools and MCP-compatible clients (such as AI agents) to perform website scraping with dynamic rendering and structured data extraction through the Oxylabs Web API.

### Features
- **Official Oxylabs MCP integration**
  - Maintained by Oxylabs as the official MCP integration for the Oxylabs Web API.

- **Website scraping via Oxylabs Web API**
  - Connects MCP clients to Oxylabs’ Web API for fetching web pages.
  - Suitable for automating web data collection through tool calls.

- **Dynamic rendering support**
  - Enables scraping of sites that require client-side rendering (e.g., JavaScript-heavy pages), via Oxylabs Web API’s dynamic rendering capabilities.

- **Structured data extraction**
  - Supports extracting structured data from scraped pages using Oxylabs Web API responses.

- **MCP server configuration**
  - Provides a `server.json` configuration file for easy registration as an MCP server.
  - Includes `smithery.yaml` for compatibility with Smithery-style MCP registries.

- **Containerized deployment**
  - Includes a `Dockerfile` for running the MCP server in a containerized environment.

- **Python-based implementation**
  - Distributed as a Python project (`pyproject.toml`).
  - Includes a test suite under `tests/`.

- **Open-source tooling**
  - Source code available on GitHub.
  - Licensed under the MIT license for flexible reuse and integration.

### Pricing
- The MCP server itself is **open source and free to use** under the MIT license.  
- Any **usage-based costs for the Oxylabs Web API** are **not specified** in this repository and would be subject to Oxylabs’ separate API pricing.