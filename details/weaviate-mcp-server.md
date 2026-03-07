## Overview

Weaviate's vector search capabilities can now be integrated through a Weaviate MCP server. The Model Context Protocol (MCP) provides a consistent method for providing context to AI models. The mcp-server-weaviate is designed to work with Weaviate vector search engine, enabling users to manage and query their data effectively.

## Available Implementations

There are multiple MCP server implementations for Weaviate:

### 1. Official Weaviate MCP Server
Supports:
- Retrieving objects from Weaviate with hybrid search
- Inserting objects into Weaviate

Official repository: github.com/weaviate/mcp-server-weaviate

### 2. Community Implementation (FastMCP-based)
Provides seamless integration with Weaviate vector databases with 11 tools including:
- Configuration viewing
- Connection checking
- Collection listing
- Schema retrieval

## Search Capabilities

### Vector Similarity Search
Using embeddings for finding conceptually similar content

### BM25 Keyword Search
Exact term matching for precise keyword queries

### Hybrid Search
Combines semantic and keyword search using Reciprocal Rank Fusion (RRF) for optimal results

## Key Features

- Powerful search capabilities across different search paradigms
- Schema management and object manipulation
- Integration with AI agents for context-aware retrieval
- Support for both semantic understanding and exact keyword matching

## Use Cases

- Semantic search in knowledge bases
- Hybrid search for e-commerce catalogs
- Document retrieval for RAG applications
- Context-aware AI agent memory
- Multi-modal search across text and embeddings

## Integration

Works with Claude Desktop, Cursor, and other MCP-compatible AI assistants for vector search operations.