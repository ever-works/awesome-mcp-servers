# DeepWiki MCP Server

RAG-as-a-Service MCP server providing open retrieval-augmented generation and knowledge access for MCP-compatible agents.

---

## Overview

DeepWiki MCP Server is a free, remote, no-authentication-required Model Context Protocol (MCP) service that offers programmatic access to DeepWiki’s public repository documentation and search capabilities (Ask Devin). It focuses on public GitHub repositories, enabling AI agents and MCP clients to retrieve documentation structure, contents, and AI-grounded answers about repositories.

- **Type:** MCP server / RAG-as-a-Service
- **Base Server URL:** `https://mcp.deepwiki.com/`
- **SSE Endpoint:** `https://mcp.deepwiki.com/sse`
- **Scope:** Public GitHub repositories
- **Auth:** No authentication required
- **Brand:** Devin / DeepWiki

---

## Features

### MCP Compatibility
- Implements the **Model Context Protocol (MCP)** for standardized integration with MCP-compatible AI apps and IDEs.
- Can be used by tools/editors that support MCP (e.g., Windsurf, Cursor, Claude Code, etc.).
- Provides endpoints suitable for:
  - **SSE (Server-Sent Events)** streaming at `/sse`.
  - **Streamable HTTP** interface at `/mcp` (per docs navigation section).

### Public GitHub Repository Knowledge Access
- Designed for **public repositories** (no private-repo auth flow described).
- Uses DeepWiki’s repository documentation system to expose structured knowledge about repositories.

### Retrieval-Augmented Generation (RAG)
- Acts as **RAG-as-a-Service**: combines retrieval over repo documentation with model-generated answers.
- Answers are **context-grounded** in the underlying repository docs via DeepWiki and Ask Devin capabilities.

### Available Tools

1. **`read_wiki_structure`**
   - Retrieves a list of documentation topics for a given GitHub repository.
   - Provides a high-level structure / table-of-contents style view of the repo’s DeepWiki docs.

2. **`read_wiki_contents`**
   - Returns documentation content for a specified topic or section in a GitHub repository.
   - Enables agents to inspect detailed docs, guides, or technical explanations associated with the repo.

3. **`ask_question`**
   - Accepts a natural-language question about a GitHub repository.
   - Responds with an **AI-powered, context-grounded** answer based on the repo documentation and related knowledge.
   - Intended for “Ask Devin”-style Q&A workflows over repo knowledge.

### Usage & Integration Characteristics
- **Remote service**: no need to self-host; connects directly to `https://mcp.deepwiki.com/`.
- **No authentication required**: simplifies setup in MCP clients.
- Optimized for use within **Devin** workflows but usable by any MCP-compliant client.

---

## Pricing

- **Cost:** Free
- **Access model:** Public, remote, no-authentication-required service for public GitHub repositories.

(Documentation does not list any paid tiers or usage-based pricing for this MCP server.)

---

## Category
- **Directory Category:** ai-integration-mcp-servers

## Tags
- rag
- knowledge-base
- ai-integration