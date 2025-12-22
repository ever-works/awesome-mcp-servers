# BigQuery MCP Server (LucasHild)

An open-source Model Context Protocol (MCP) server that provides LLMs with direct access to Google BigQuery for schema inspection and SQL query execution.

## Key Details
- **Type:** MCP server / developer tool
- **Category:** mcp-server-directories-lists
- **Ecosystem / Brand:** Google Cloud BigQuery
- **License:** MIT
- **Source Code:** https://github.com/LucasHild/mcp-server-bigquery
- **Slug:** `bigquery-mcp-server-lucashild`

## Features
- **BigQuery integration**
  - Connects to Google BigQuery datasets.
  - Enables inspection of database schemas.
  - Executes SQL queries directly against BigQuery.

- **LLM-oriented server**
  - Implements the Model Context Protocol (MCP) so LLMs and MCP-compatible clients can interact with BigQuery in a structured way.

- **Open-source implementation**
  - Source available on GitHub.
  - Licensed under MIT for flexible reuse and modification.

- **Python-based project**
  - Managed via `pyproject.toml`.
  - Includes a `.python-version` file for consistent Python environment setup.

- **Containerization support**
  - Includes a `Dockerfile` for building container images and running the server in containerized environments.

- **Repository tooling & config**
  - `.github` directory for GitHub-related workflows/configuration.
  - `smithery.yaml` present for integration with Smithery-style MCP tooling (configuration-based setup).

## Pricing
- **Free and open source** under the MIT license (no license fee).