# FileStack MCP Server

## Overview
FileStack MCP Server is an MCP-compatible service from Pipedream that exposes Filestack’s file handling capabilities (uploading, transforming, and delivering files) to MCP-based tools and chat clients via a static MCP server URL.

- **Type:** MCP server / developer tool
- **Provider / Brand:** Pipedream
- **Category:** File management MCP servers
- **Use cases:** File upload, file processing and transformation, CDN-style delivery within MCP-enabled applications

## Features
- **MCP-based integration**
  - Exposes Filestack file handling capabilities to any MCP-compatible client.
  - Integrates with chat clients and tools that support MCP servers.

- **Static MCP server endpoint**
  - Single static URL for all clients: `https://mcp.pipedream.net/v2`.
  - Authentication handled when adding the server to your application.

- **File handling capabilities (via Filestack)**
  - Uploading files (developer-focused file ingestion).
  - Transforming / processing files (e.g., image or document transformations, based on Filestack capabilities).
  - Delivering files, suitable for CDN-like usage.

- **Client configuration flow**
  - Connect a Filestack/Pipedream account and select a client to get started.
  - Per-client setup instructions available via the configuration flow.
  - Central configuration reference via the dedicated configuration page.

- **Tool discovery**
  - MCP server exposes available tools / actions that can be listed by compatible clients (e.g., “Loading actions…”, “Loading available tools…”).

## Configuration
- Use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-compatible app or chat client.
- Authenticate during the add/connect flow.
- Optionally consult the full configuration page on Pipedream for detailed setup steps.

## Tags
- File management
- File processing
- CDN

## Pricing
- Not specified in the provided content.