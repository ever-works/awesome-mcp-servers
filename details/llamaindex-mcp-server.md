## Overview

LlamaIndex offers multiple ways to use MCP servers, allowing you to bring additional resources and functionality to your agentic workflows. The integration provides seamless access to LlamaCloud's powerful indexing and data extraction capabilities through the Model Context Protocol standard.

## Key Integration Patterns

There are three primary integration patterns:

### 1. Using MCP servers with LlamaIndex
Get data from external resources that are served via existing MCP servers.

### 2. Serving LlamaIndex as MCP
You can convert your own custom LlamaIndex workflows to MCP servers.

### 3. LlamaCloud MCP services
Run MCP servers (both in Python and Typescript) that serve LlamaCloud functionality such as LlamaExtract or LlamaParse.

## Context Retrieval Capabilities

- **Query Managed Vector Indexes**: Knowledge retrieval from pre-indexed data
- **LlamaCloud Integration**: Access to LlamaCloud's indexing and data extraction
- **Hybrid Approach**: Mix of MCP tools that directly connect to third-party services and retrieval tools over pre-indexed data

## Getting Tools from MCP Servers

Using the `get_tools_from_mcp_url` or `aget_tools_from_mcp_url` function, you can get a list of FunctionTools from an MCP server. MCPToolSpec will get the tools from MCP Client and convert them to LlamaIndex's FunctionTool objects.

## Best Practices

The best agents will use a mix of MCP tools:
- **Direct Connection Tools**: Tools that directly connect to third-party services
- **Retrieval Tools**: Fast lookup through pre-processed indexes
- **Deep Dive Tools**: Deep dives into specific data sources through native MCP interfaces

## MCP vs. Vector Search

This approach enables both fast lookup through pre-processed indexes and deep dives into specific data sources through native MCP interfaces, combining the strengths of both approaches.

## Use Cases

- RAG (Retrieval Augmented Generation) applications
- Knowledge base queries
- Document analysis and extraction
- Multi-source data retrieval
- Agentic workflows with external tool access