# Parallel Search MCP Server

**Category:** Web Search MCP Servers  
**Vendor:** parallel-web-systems  
**OAuth2.1 Endpoint / Server URL:** `https://search-mcp.parallel.ai/mcp`  
**Source:** https://docs.parallel.ai/integrations/mcp/search-mcp

## Overview

Parallel Search MCP Server is an MCP-compatible HTTP server that adds real-time web search and content extraction to any MCP-aware AI client or agent. It wraps the Parallel Search API in an agent-friendly interface and uses the API in `agentic` mode to return concise, structured results suitable for tool-using LLMs.

## Features

- **MCP-Compatible HTTP Server**  
  - Exposes tools over MCP at `https://search-mcp.parallel.ai/mcp`  
  - Works with any MCP-aware model or client (e.g., Cursor, VS Code MCP integrations, and other MCP-capable tools).

- **`web_search` Tool**  
  - Performs web searches for up-to-date information.  
  - Retrieves relevant results using the Parallel Search API.  
  - Operates in `agentic` mode for more concise, agent-optimized responses vs. `one-shot` mode.  
  - Suitable for:
    - Real-time fact checking and verification during conversations.
    - Answering questions that require current or live data.
    - Topic research that benefits from recent web content.
    - Competitive intelligence and market research.

- **`web_fetch` Tool**  
  - Fetches and extracts content from specific URLs.  
  - Designed for downstream analysis or summarization by AI agents.  
  - Useful for workflows that need structured content from known web pages.

- **Agent-Optimized Interface**  
  - Simplifies the underlying Search API into tools that are easy for agents to call correctly.  
  - Uses `agentic` search mode to minimize noise and provide focused, summarized results.

- **Content Extraction**  
  - Extracts page content from specified URLs via `web_fetch`.  
  - Integrates seamlessly with search results when agents need full-page context.

- **Programmatic Use with Parallel API Key**  
  - Can be used programmatically by setting the `Authorization: Bearer <PARALLEL_API_KEY>` header.  
  - Integrates with the broader Parallel Web Systems platform and Search API.

- **Client Integration Examples**  
  - **Cursor**
    - Configure in `~/.cursor/mcp.json` or project-level `.cursor/mcp.json`.  
    - Example (conceptual) entry: points `"Parallel Search MCP"` to `"https://search-mcp.parallel.ai/mcp"`.  
    - Deep link to install: `https://cursor.com/en/install-mcp?name=Parallel%20Search%20MCP&config=eyJ1cmwiOiJodHRwczovL3NlYXJjaC1tY3AucGFyYWxsZWwuYWkvbWNwIn0=`
  - **VS Code**
    - Configure MCP servers in `settings.json`.  
    - Example (conceptual) entry: MCP server named `"Parallel Search MCP"` of type `"http"` with URL `"https://search-mcp.parallel.ai/mcp"`.

## Use Cases

- Real-time fact checking and verification during AI-assisted conversations.  
- Answering user questions that require the latest or live web information.  
- Research workflows needing recent sources and web documents.  
- Retrieving and analyzing content from specific URLs (e.g., articles, docs, reports).  
- Competitive intelligence and market monitoring using current web data.

## Installation & Configuration

- **Server URL**: `https://search-mcp.parallel.ai/mcp`  
- **Authentication (programmatic)**: Provide a Parallel API key as a Bearer token in the `Authorization` header when required.  
- **MCP Clients**: Add the server configuration to your MCP client’s settings (e.g., `mcp.json` for Cursor, `settings.json` for VS Code) naming the server "Parallel Search MCP" and pointing to the above URL.

## Pricing

- The provided content does not specify pricing or plans for the Parallel Search MCP Server. Refer to the Parallel pricing page (`/resources/pricing`) if you need current pricing details.