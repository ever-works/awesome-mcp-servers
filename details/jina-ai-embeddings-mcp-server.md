## Overview

The Jina AI MCP server is a remote Model Context Protocol server that provides access to Jina Reader, Embeddings and Reranker APIs with a suite of URL-to-markdown, web search, image search, and embeddings/reranker tools.

## Features

### Search Tools

- **search_web**: Searches the web for current information
- **parallel_search_web**: Runs multiple web searches in parallel for comprehensive coverage
- **search_arxiv**: Searches academic papers on the arXiv repository

### Embeddings & Reranking Tools

- **sort_by_relevance**: Reranks documents based on relevance to a query using Jina's Reranker API
- **deduplicate_strings**: Finds semantically unique strings from a list using Embeddings API

### Additional Tools

- URL-to-markdown conversion
- Image search capabilities
- Content extraction and processing

## Embeddings API

Jina offers top-performing multimodal multilingual long-context embeddings for search, RAG, and agent applications.

### jina-embeddings-v4

Their most significant model:
- **3.8B parameters**
- Embeds text and images through a unified pathway
- Multimodal capabilities
- Long-context support
- State-of-the-art performance

## Setup and Access

Add to Claude using:
```bash
claude mcp add -s user --transport http jina https://mcp.jina.ai/v1 --header "Authorization: Bearer ${JINA_API_KEY}"
```

### API Key Requirements

- Optional tools work without an API key (with rate limits)
- For higher rate limits and better performance, use a Jina API key
- Free tier available with limitations

## Use Cases

- Semantic search applications
- Retrieval Augmented Generation (RAG) systems
- AI agent memory and context
- Multimodal search (text + images)
- Document deduplication
- Content relevance ranking
- Academic paper research

## Integration

Compatible with:
- Claude Desktop and Claude Code
- Any MCP-compatible client
- Custom SDK integrations

## Technical Specifications

- Remote MCP server (HTTPS transport)
- OAuth authentication support
- Rate limiting controls
- Batch processing capabilities

## Pricing

Free tier available with rate limits. Premium tiers for production use with higher quotas and SLA.