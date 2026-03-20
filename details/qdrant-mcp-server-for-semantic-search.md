## Overview

Qdrant MCP Server provides semantic search capabilities through integration with Qdrant vector database and multiple embedding providers. It enables AI assistants to perform intelligent similarity search and information retrieval using state-of-the-art embedding models.

## Supported Embedding Providers

### Ollama
- Local embedding models
- Privacy-focused deployment
- No external API calls
- Custom model support

### OpenAI
- text-embedding-3-small
- text-embedding-3-large  
- text-embedding-ada-002
- High-quality embeddings

### Cohere
- embed-english-v3.0
- embed-multilingual-v3.0
- Specialized for search
- Strong multilingual support

### Voyage AI
- voyage-3
- voyage-code-3
- Domain-optimized embeddings
- Excellent code understanding

## Features

### Semantic Search
- Natural language queries
- Similarity-based retrieval
- Hybrid search (dense + sparse)
- Multi-vector search
- Filtered search with metadata

### Collection Management
- Create and manage collections
- Configure vector dimensions
- Index optimization
- Snapshot and backup

### Vector Operations
- Insert and update vectors
- Batch operations
- Delete by ID or filter
- Point payload management

### Advanced Features
- Recommendation system
- Clustering and grouping
- Scroll through results
- Quantization for efficiency

## Use Cases

- Semantic document search
- Question answering systems
- Recommendation engines
- Duplicate detection
- Content discovery
- Knowledge base retrieval
- Code search
- Image similarity search

## Local Deployment

Supports local Qdrant deployment:
- Docker container
- Binary installation
- In-memory mode
- Persistent storage

## Cloud Option

Qdrant Cloud integration:
- Managed hosting
- Automatic scaling
- Global distribution
- Enterprise features

## Performance

- Fast nearest neighbor search
- Hardware acceleration support
- Efficient memory usage
- Parallel processing
- Query result caching

## Technical Implementation

Built with Qdrant client libraries providing native integration with the vector database. Supports both gRPC and REST API protocols.

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Works with local Qdrant instances or Qdrant Cloud.

## Configuration

Flexible configuration for:
- Embedding provider selection
- Model parameters
- Collection settings
- Search parameters
- Connection options