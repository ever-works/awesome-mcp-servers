# Needle MCP Server

**Website:** https://github.com/needle-ai/needle-mcp  
**Category:** AI Integration – MCP Servers  
**Brand:** needle

## Overview

Needle MCP Server is a Model Context Protocol (MCP) server that connects Needle’s retrieval-augmented generation (RAG) and long‑term memory capabilities to LLM-based agents (e.g., via Claude Desktop). It provides a unified MCP endpoint for managing documents and running searches over a knowledge base, enabling RAG-as-a-service for compatible LLM clients.

## Features

- **MCP-compliant server**  
  - Implements the Model Context Protocol to integrate with MCP-compatible LLM tools (such as Claude Desktop).

- **RAG-as-a-service integration**  
  - Exposes Needle’s retrieval-augmented generation capabilities through a single MCP endpoint.  
  - Designed to give LLMs persistent, searchable context over external documents.

- **Long-term memory for LLMs**  
  - Treats stored documents and knowledge as a long‑term memory layer that LLMs can query through standardized MCP tools.

- **Document management**  
  - Server endpoints to manage documents in Needle (e.g., add/update/remove documents in the knowledge base).  
  - Organizes content so it can be retrieved and used in responses by the LLM.

- **Search and retrieval tools**  
  - Tools/commands to perform searches against Needle’s index from within the LLM interface.  
  - Oriented toward semantic or knowledge-base-style queries rather than simple keyword search.

- **Agent/desktop app integration**  
  - Explicitly intended for use with Claude’s Desktop Application via MCP.  
  - Can be used to “build agents” that call the Needle MCP tools during conversations.

- **Containerized deployment**  
  - Includes a `Dockerfile` for container-based deployment.

- **Python-based implementation**  
  - Python project with configuration in `pyproject.toml`.  
  - Includes a `smithery.yaml` for integration with Smithery tooling.

- **Open source licensing**  
  - Distributed under the MIT License.

## Pricing

No pricing information is provided in the available content. The repository itself is open source under the MIT license; any separate pricing for the underlying Needle service is not specified here.