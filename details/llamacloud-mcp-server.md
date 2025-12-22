# LlamaCloud MCP Server

TypeScript-based MCP server for integrating and querying data stored in managed indexes on LlamaCloud (LlamaIndex’s hosted service), enabling retrieval-augmented workflows over cloud indexes.

## Overview
LlamaCloud MCP Server connects to multiple managed indexes hosted on LlamaCloud and exposes them as tools via the Model Context Protocol (MCP). This allows AI agents or MCP-compatible clients to perform retrieval-augmented generation (RAG) and other knowledge-intensive tasks over centralized cloud indexes.

## Features
- **MCP server implementation**
  - Implements a Model Context Protocol (MCP) server for use with MCP-compatible clients and agents.
- **Integration with LlamaCloud**
  - Connects directly to managed indexes hosted on [LlamaCloud](https://cloud.llamaindex.ai/), LlamaIndex’s managed service.
- **Multiple index support**
  - Connects to **multiple** managed indexes in a single server instance.
  - Creates **multiple tools**, each associated with a specific managed index.
- **Retrieval over managed indexes**
  - Enables querying and retrieval over data stored in LlamaCloud indexes.
  - Designed for retrieval-augmented workflows where external knowledge from cloud indexes is injected into model context.
- **Built on LlamaIndex ecosystem**
  - Uses LlamaIndex’s hosted infrastructure (LlamaCloud) for data indexing and retrieval.
- **TypeScript-based**
  - Implemented in TypeScript, suitable for Node.js/JavaScript environments.

## Use Cases
- Powering retrieval-augmented generation (RAG) from LlamaCloud indexes via MCP.
- Exposing multiple organizational or project-specific indexes as separate tools for an AI agent.
- Centralizing access to different knowledge bases (e.g., documentation, knowledge graphs, internal datasets) through a single MCP server.

## Technical Details
- **Language:** TypeScript
- **Protocol:** Model Context Protocol (MCP)
- **Backend Service:** LlamaCloud (LlamaIndex hosted managed indexes)
- **Source:** GitHub repository – `run-llama/mcp-server-llamacloud`

## Pricing
- No pricing information is provided in the available content.
- Distributed as source code on GitHub; consult the repository’s `LICENSE` file and documentation for licensing and usage terms.