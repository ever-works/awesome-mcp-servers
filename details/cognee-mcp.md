# cognee-mcp

**Category:** MCP Server – Directories & Lists  
**Slug:** `cognee-mcp`

## Description
cognee-mcp is a Model Context Protocol (MCP) server that exposes Cognee’s memory engine, with a focus on GraphRAG-style workflows. It lets you ingest, process, and search graph-based knowledge representations and make that memory accessible to agents and any MCP-compatible client (e.g., terminal or IDE integrations).

## Features
- **GraphRAG-focused memory engine**
  - Works with graph-based knowledge representations.
  - Supports customizable data ingestion, processing, and search over knowledge graphs.

- **MCP server integration**
  - Runs Cognee’s memory engine as an MCP server.
  - Usable from any client that speaks MCP (e.g., terminal tools, IDE plugins).

- **Multiple transport options**
  - **HTTP (Streamable)**: `--transport http` – recommended for web deployments.
  - **SSE (Server-Sent Events)**: `--transport sse` – real-time streaming.
  - **stdio**: classic pipe mode (default).

- **API Mode**
  - Can connect to an already running Cognee FastAPI backend instead of running Cognee directly inside the MCP process.
  - Useful for deployments where a central Cognee API is shared across clients.

- **Integrated logging**
  - All actions logged to a rotating log file (see `get_log_file_location()` in the codebase).
  - Logs are mirrored to the console in development environments.

## Pricing
- Open-source project hosted on GitHub.  
- No pricing plans or commercial tiers are specified in the available documentation.

## Links
- **Source Code:** https://github.com/topoteretes/cognee/tree/main/cognee-mcp
- **Project Website (Cognee):** https://cognee.ai