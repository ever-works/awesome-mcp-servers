## Overview

LangChain MCP Adapters provide seamless integration between the Model Context Protocol and LangChain ecosystem. These adapters convert MCP tools into LangChain-compatible tools that can be used with LangGraph agents and other LangChain components.

## Features

### Tool Conversion
- **MCP to LangChain**: Automatic conversion of MCP tools to LangChain tools
- **Schema Mapping**: Preserve tool schemas and metadata
- **Type Safety**: Maintain type information across conversion
- **Error Handling**: Unified error handling between protocols

### Client Implementation
- **Multi-Server Support**: Connect to multiple MCP servers simultaneously
- **Server Discovery**: Automatic discovery of available tools
- **Connection Management**: Handle server lifecycle and reconnection
- **Authentication**: Support for various auth methods
- **Transport Negotiation**: Automatic transport protocol selection

### LangGraph Integration
- **Agent Tools**: Use MCP tools directly in LangGraph agents
- **Tool Calling**: Native support for LangGraph tool calling
- **State Management**: Integrate with LangGraph state machines
- **Streaming Support**: Real-time tool execution with streaming

## Use Cases

- Building LangGraph agents with MCP tools
- Connecting LangChain applications to MCP servers
- Multi-server orchestration in LangChain workflows
- Migrating existing MCP tools to LangChain
- Creating hybrid MCP/LangChain applications
- Enterprise tool aggregation

## Architecture

### Adapter Layer
The adapter layer handles protocol translation, ensuring seamless communication between LangChain and MCP servers while preserving tool semantics and behavior.

### Client Layer
The client implementation manages connections, authentication, and communication with MCP servers, supporting multiple concurrent server connections.

### Tool Registry
Centralized registry of available tools from all connected MCP servers, enabling dynamic tool discovery and usage.

## Integration Patterns

### Single Server Integration
```python
# Connect to one MCP server and use its tools in LangChain
```

### Multi-Server Orchestration
```python
# Connect to multiple MCP servers and aggregate tools
```

### Dynamic Tool Loading
```python
# Dynamically discover and load tools at runtime
```

## Technical Implementation

Built and maintained by LangChain team, ensuring compatibility with latest LangChain and LangGraph versions. Follows LangChain's tool interface standards and conventions.

## Integration

Works with any MCP-compliant server and integrates seamlessly with LangChain, LangGraph, LangSmith, and the broader LangChain ecosystem.

## Performance

Optimized for minimal overhead with efficient tool conversion, connection pooling, and caching strategies for frequently used tools.