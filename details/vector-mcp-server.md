## Overview

Vector MCP Server is a standardized collection management system across vector database technologies, supporting ChromaDB, PGVector, Couchbase, Qdrant, and MongoDB. It allows AI Agents to perform hybrid search for document information (lexical/vector), create collections with documents stored on the local filesystem or URLs, and utilize collections for retrieval augmented generation (RAG).

## Features

- **Multi-Database Support**: Single interface for ChromaDB, Couchbase, MongoDB, Qdrant, and PGVector
- **Hybrid Search**: Combine lexical and vector search for optimal retrieval
- **Collection Management**: Create and manage document collections across different vector databases
- **Document Sources**: Support for local filesystem and URL-based documents
- **RAG Implementation**: Built for retrieval augmented generation use cases
- **Standardized Interface**: Consistent API across different vector database backends

## Supported Vector Databases

- **ChromaDB**: In-memory and persistent vector storage
- **Couchbase**: Enterprise NoSQL with vector search capabilities
- **MongoDB**: Document database with Atlas Vector Search
- **Qdrant**: High-performance vector similarity search engine
- **PGVector**: PostgreSQL extension for vector embeddings

## Use Cases

- Building RAG applications with multiple vector database backends
- Semantic search across document collections
- AI agents with long-term memory capabilities
- Multi-modal search combining text and metadata
- Cross-database vector search evaluation

## Technical Implementation

Heavily inspired by the RAG implementation of Microsoft's Autogen V1 framework, providing a battle-tested approach to vector-based retrieval.

## Pricing

Free and open-source. Individual database hosting costs may apply.