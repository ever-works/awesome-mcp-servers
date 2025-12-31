# Bitable MCP

**Category:** Data Access & Integration – MCP Servers  
**Brand:** Lark  
**Repository:** https://github.com/lloydzhou/bitable-mcp

## Overview
Bitable MCP is a Model Context Protocol (MCP) server that connects Lark Bitable with LLM clients. It exposes predefined tools so language models can read and manipulate data in Lark Bitable tables programmatically.

## Features
- **Lark Bitable integration**
  - Provides access to Lark Bitable as a backend data source.
  - Supports interaction with Bitable tables via structured MCP tools.

- **Model Context Protocol server**
  - Implements the MCP specification so it can be used by compatible LLM clients (e.g., Claude Desktop).
  - Encapsulates table operations as tools that can be invoked by the model.

- **Table data operations**
  - Read data from Bitable tables (e.g., querying table contents).
  - Manipulate table data (e.g., create/update/delete rows or fields) via predefined tools. *(Exact operations are not fully listed in the source content, but read and manipulation are explicitly mentioned.)*

- **One‑click / scripted installation**
  - Installable via **Smithery** for Claude Desktop:
    ```bash
    npx -y @smithery/cli install @lloydzhou/bitable-mcp --client claude
    ```
  - Includes configuration instructions for Claude Desktop (in the repository README).

- **Containerized deployment**
  - Includes a `Dockerfile` for building and running the MCP server in a containerized environment.

- **Python-based project**
  - Managed via `pyproject.toml` with pinned dependencies in `uv.lock`.

## Installation
- **Via Smithery (Claude Desktop):**
  ```bash
  npx -y @smithery/cli install @lloydzhou/bitable-mcp --client claude
  ```
- Additional configuration steps are provided in the repository’s `README.md`.

## Pricing
No pricing or plans are listed in the provided content; the project appears to be an open-source GitHub repository.