## Overview

The Knowledge Graph Memory Server is an official, open-source MCP server provided by Anthropic that enables Claude to remember information about users across chats by maintaining a local knowledge graph. It stores entities, relations, and observations in a persistent format.

## Core Components

The system uses three main components:

### 1. Entities
The primary nodes in the knowledge graph, each with:
- Unique name (identifier)
- Entity type (e.g., "person", "organization", "event")
- List of observations

### 2. Relations
Always stored in active voice and describe how entities interact or relate to each other.

### 3. Observations
Discrete pieces of information about an entity:
- Stored as strings
- Attached to specific entities
- Should be atomic (one fact per observation)

## Installation

The server can be installed using:
```bash
claude mcp add-json "memory" '{"command":"npx","args":["-y","@modelcontextprotocol/server-memory"]}'
```

## License

The MCP server is licensed under the MIT License, meaning you are free to use, modify, and distribute the software.

## Official Repository

GitHub repository: github.com/modelcontextprotocol/servers/tree/main/src/memory

## Key Features

- **Persistent Memory**: Information persists across chat sessions
- **Knowledge Graph Structure**: Organized, queryable knowledge representation
- **Entity Relationships**: Track complex relationships between entities
- **Atomic Observations**: Fine-grained fact storage
- **Official Anthropic Support**: Maintained as part of the official MCP reference servers

## Use Cases

- User preference tracking across sessions
- Building long-term AI assistant memory
- Knowledge base construction
- Relationship mapping
- Context maintenance for personalized AI interactions

## Integration

Works with Claude Desktop and other MCP-compatible clients to provide persistent memory capabilities.