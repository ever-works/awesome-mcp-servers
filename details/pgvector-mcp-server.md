## Overview

The PGVector MCP Server provides semantic search capabilities for PostgreSQL databases using vector embeddings. It enables AI assistants to perform similarity searches, metadata filtering, and document insertion with automatic embedding generation.

## Features

- **Semantic Similarity Search**: Perform vector-based similarity searches using embeddings
- **Metadata Filtering**: Search documents by metadata filters
- **Statistics**: Get statistics about vector-enabled tables
- **Status Checking**: Check server status, database connectivity, and available functionality
- **Multiple Embedding Providers**: Support for Azure OpenAI and Hugging Face
- **Automatic Embeddings**: Generate embeddings automatically during document insertion

## Technical Details

Requires:
- PostgreSQL 14+ with pgvector extension
- Configured via DATABASE_URL environment variable
- SQL operators for similarity: Euclidean distance (<->), cosine similarity (<=>), negative inner product (<#>)
- HNSW or IVFFlat indexes for large-scale approximate nearest neighbor searches

## Use Cases

- Semantic document search and retrieval
- Retrieval Augmented Generation (RAG) systems
- Knowledge base question answering
- Content recommendation systems
- Similarity-based data analysis

## Vector Search Operations

Developers can store, index and query vectors in PostgreSQL using pgvector, eliminating the need for a dedicated vector database. The extension provides SQL operators for various distance metrics and supports indexing strategies for performance optimization.

## Pricing

Free and open-source. Embedding provider costs may apply.