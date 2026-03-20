## Overview

A vector search MCP server for document retrieval using MongoDB Atlas Vector Search and Voyage AI Context embeddings. This implementation provides semantic search capabilities for markdown documents by processing them into chunks with hierarchical structure and generating high-quality embeddings.

## Key Features

### Document Processing

- **Markdown Ingestion**: Ingests and chunks markdown documents with hierarchical headers
- **Hierarchical Chunking**: Maintains document structure with parent-child relationships
- **Contextual Embeddings**: Generates embeddings using Voyage AI's contextual embeddings API
- **MongoDB Storage**: Stores documents and embeddings in MongoDB with relationships

### Search Capabilities

- **Semantic Search**: Provides FastMCP server for semantic document search
- **Intelligent Querying**: Query across markdown documentation using natural language
- **Contextual Understanding**: Leverages hierarchical structure for better results
- **Vector Similarity**: Uses MongoDB Atlas Vector Search for fast retrieval

## Technical Architecture

### Components

1. **Document Processor**: Chunks markdown with header hierarchy
2. **Embedding Generator**: Uses Voyage AI for contextual embeddings
3. **Vector Store**: MongoDB Atlas with vector search indexes
4. **MCP Server**: FastMCP server implementation
5. **Query Engine**: Semantic search with context awareness

### MongoDB Integration

- MongoDB Atlas cluster with vector search enabled
- Automatic quantization capabilities
- Support for Voyage AI's quantization-aware embedding models
- Efficient vector similarity operations

## Voyage AI Embeddings

MongoDB officially recommends Voyage AI for state-of-the-art embedding models:

- Contextual embeddings for better semantic understanding
- Quantization-aware models for efficient storage
- High-quality representations for document retrieval
- Optimized for MongoDB Atlas Vector Search

## Setup Requirements

- MongoDB Atlas cluster with vector search enabled
- Voyage AI API key
- Markdown documentation to index
- FastMCP server runtime

## Use Cases

- Technical documentation search
- Knowledge base question answering
- API documentation retrieval
- Code documentation exploration
- Multi-document semantic search
- Context-aware information retrieval

## Integration

Works with AI assistants and applications that support MCP protocol:
- Claude Code and Claude Desktop
- Cursor IDE
- Custom MCP clients
- Any MCP-compatible tool

## Benefits

- Fast semantic search across large documentation sets
- Maintains document context and hierarchy
- Efficient vector storage and retrieval
- High-quality embeddings from Voyage AI
- Scalable MongoDB Atlas infrastructure

## Pricing

Open-source server. Costs include:
- MongoDB Atlas (free tier available)
- Voyage AI API usage (varies by volume)