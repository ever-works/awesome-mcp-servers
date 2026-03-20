## Overview

Jina AI MCP Server is the official remote Model Context Protocol server from Jina AI, providing comprehensive access to Jina's Search Foundation APIs. It enables AI assistants to leverage Jina Reader for content extraction, Embeddings API for semantic understanding, and Reranker for result optimization.

## Features

### Jina Reader API
- **URL-to-Markdown Conversion**: Convert web pages to clean markdown format
- **Content Extraction**: Extract structured content from web pages
- **Web Search**: Perform web searches with AI-optimized results
- **Image Search**: Search and retrieve images from the web
- **Clean Output**: Remove ads, navigation, and other noise from content

### Embeddings API
- **Text Embeddings**: Generate high-quality embeddings for text
- **Image Embeddings**: Create embeddings for visual content
- **Unified Pathway**: Process both text and images through a single model
- **Semantic Deduplication**: Remove duplicate content using vector similarity
- **Multilingual Support**: Handle text in multiple languages
- **Code Embeddings**: Specialized embeddings for source code

### Reranker API
- **Result Reranking**: Optimize search result ordering
- **Relevance Scoring**: Calculate semantic relevance scores
- **Cross-Encoder Architecture**: Advanced reranking using cross-encoders

### Deduplication Tools
- **String Deduplication**: Remove duplicate strings using submodular optimization
- **Semantic Similarity**: Identify similar content across different wording
- **Diversity Selection**: Select diverse yet relevant items from collections

## Use Cases

- Web content extraction and analysis
- Semantic search implementations
- RAG (Retrieval-Augmented Generation) pipelines
- Content deduplication
- Multi-modal search applications
- Document similarity analysis
- Code search and retrieval
- Knowledge base construction

## Technical Implementation

Built and maintained by Jina AI with full API compatibility. Jina-embeddings-v4 (3.8B parameters) outperforms proprietary models from Google, OpenAI, and Voyage AI on visually rich document retrieval tasks.

## API Compatibility

Jina API endpoints match OpenAI's text-embedding-3-large input/output JSON schemas, making it easy to switch between providers.

## Integration

Remote MCP server accessible via HTTP, compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Requires Jina AI API key for authentication.