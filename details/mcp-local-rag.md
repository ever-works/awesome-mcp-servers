# mcp-local-rag

## Overview
mcp-local-rag is a local, "primitive" retrieval-augmented generation (RAG)-style Model Context Protocol (MCP) server. It uses Google’s MediaPipe Text Embedder together with DuckDuckGo Search to provide web search and RAG-style context retrieval for AI assistants, without relying on external paid APIs.

- **Type:** Open-source MCP server
- **Author/Brand:** nkapila6
- **Category:** Web search MCP servers
- **License:** MIT
- **Repository:** https://github.com/nkapila6/mcp-local-rag

## Features
- **Local RAG-style server**
  - Implements a "primitive" RAG workflow for providing contextual information to AI assistants.
  - Runs locally on the user’s machine.

- **No external paid APIs required**
  - Designed to operate without API keys to commercial LLM or embedding services.
  - Uses freely available components for both embeddings and search.

- **MediaPipe Text Embedder integration**
  - Uses Google’s MediaPipe Text Embedder to generate text embeddings locally.
  - Avoids dependence on cloud-based embedding services.

- **DuckDuckGo web search**
  - Uses DuckDuckGo Search as the web search backend.
  - Enables retrieval of up-to-date web content for augmentation.

- **Model Context Protocol (MCP) server**
  - Exposes capabilities via MCP for integration with MCP-compatible clients (e.g., AI assistants and tools that support MCP servers).
  - Designed to provide web search and RAG retrieval as an MCP tool.

- **Local / containerized setup**
  - Includes a `Dockerfile` for containerized deployment.
  - Development helper files such as `.devcontainer` and environment/config files are present, indicating support for reproducible dev environments.

- **Python-based implementation**
  - Uses a Python environment specified by `.python-version`.
  - Source code organized under `src/mcp_local_rag`.

## Use Cases
- Augmenting local or MCP-aware AI assistants with web search results and contextual passages.
- Experiments with RAG pipelines using only local embeddings and a free web search engine.
- Developing or testing MCP clients that need simple, local web-search/RAG functionality.

## Pricing
- **Open-source (MIT License)**
  - No direct cost to use the software.
  - Users may incur normal local resource usage and network usage when performing web searches.

## Additional Details
- **Slug:** `mcp-local-rag`
- **Tags:** `rag`, `web-search`, `local-models`