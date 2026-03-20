## Overview

Claude Context is an AI-powered semantic code search system built on LanceDB's local vector database with optional enterprise-grade Milvus/Zilliz Cloud support. It provides zero-configuration semantic code navigation through the Model Context Protocol.

## Features

### Semantic Code Search
- Natural language code queries
- Find code by functionality
- Discover similar implementations
- Search across programming languages
- Context-aware results

### Local Vector Storage
- **LanceDB**: Embedded, zero-config vector database
- No external dependencies required
- Fast local indexing
- Incremental updates
- Persistent storage

### Enterprise Option
- **Milvus/Zilliz Cloud**: Production-scale deployments
- Distributed architecture
- Advanced indexing strategies
- High availability
- Team collaboration

### Code Understanding
- Function and method detection
- Class hierarchy analysis
- Import and dependency tracking
- Documentation extraction
- Code pattern recognition

## Supported Languages

- Python
- JavaScript/TypeScript
- Java
- C++/C
- Go
- Rust
- Ruby
- PHP
- And more

## Use Cases

- Codebase exploration
- Finding implementation examples
- Understanding unfamiliar code
- Refactoring assistance
- Code review
- Documentation generation
- Technical onboarding
- Architecture analysis

## Zero-Config Setup

```bash
# Install and run
npx claude-context

# Automatically indexes current directory
# No configuration needed
```

## Advanced Configuration

### LanceDB (Default)
```json
{
  "vectorDb": "lancedb",
  "storagePath": ".claude-context",
  "embeddingModel": "local"
}
```

### Milvus/Zilliz Cloud
```json
{
  "vectorDb": "milvus",
  "endpoint": "https://your-cluster.zillizcloud.com",
  "token": "your-api-token"
}
```

## Indexing Process

1. **Code Parsing**: Extract functions, classes, methods
2. **Embedding Generation**: Create semantic vectors
3. **Vector Storage**: Store in LanceDB or Milvus
4. **Index Building**: Optimize for fast retrieval

## Query Examples

- "Find functions that handle user authentication"
- "Show me database connection code"
- "Where is error handling implemented?"
- "Find API endpoint definitions"
- "Show similar code to this function"

## Performance

### LanceDB
- Instant startup
- No server required
- Sub-second queries
- Minimal memory usage

### Milvus
- Billions of vectors
- Millisecond latency
- Horizontal scaling
- Enterprise features

## Technical Implementation

Built with TypeScript, leveraging LanceDB's columnar format and Apache Arrow for efficient vector operations. Optional Milvus integration for production deployments.

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Works as a standalone tool or integrated into development workflows.