# Javadocs.dev MCP Server

**Category:** Documentation & Learning Resources  
**Brand:** javadocsdev  
**Source:** https://github.com/pankaj28843/docs-mcp-server

## Description
Javadocs.dev MCP Server is an open-source, multi-tenant Model Context Protocol (MCP) server that enables MCP-compatible tools and agents to search and retrieve Java API documentation programmatically. It uses FastMCP together with BM25-based search and an article-extraction pipeline to provide structured documentation results.

## Features
- **Model Context Protocol server**
  - Exposes documentation search and retrieval via the MCP standard.
  - Designed to plug into MCP-compatible tools and AI agents.

- **Multi-tenant architecture**
  - Supports multiple tenants/projects on a single server instance.

- **Java documentation search**
  - Focused on Java API and library documentation.
  - Allows programmatic search of Javadoc-style content.

- **Search engine based on BM25**
  - Utilizes BM25 ranking for relevance scoring of documentation.

- **FastMCP integration**
  - Built on or integrated with FastMCP for efficient MCP tooling.

- **Article/document extractor**
  - Uses an article-extractor component to pull relevant text from documentation pages before indexing or returning results.

- **Project structure and tooling**
  - `docs/` directory for project documentation.
  - `mcp-data/` for MCP-related data or configuration.
  - `src/docs_mcp_server/` for server implementation.
  - `tests/` suite for automated testing.
  - Editor and lint configuration files (`.editorconfig`, `.pylintrc`, etc.).
  - Docker-related configuration (`.dockerignore`) for containerized deployment.

- **Open-source licensing**
  - Released under the MIT License.

## Pricing
- Not specified; the project is open source under the MIT License and can be used and self-hosted freely under that license.
