# UnifAI MCP Server

## Overview
UnifAI MCP Server is an MCP (Model Context Protocol) server for the UnifAI Network that enables LLMs to dynamically discover, search, and invoke tools available on the UnifAI Network.

> Note: The UnifAI MCP server functionality has been moved into the UnifAI SDKs:
> - [UnifAI Python MCP Server](https://github.com/unifai-network/unifai-sdk-py?tab=readme-ov-file#using-tools-in-mcp-clients)
> - [UnifAI TypeScript MCP Server](https://github.com/unifai-network/unifai-sdk-js?tab=readme-ov-file#using-tools-in-mcp-clients)

## Category
- MCP middleware & orchestration

## Features
- **MCP server for UnifAI Network**
  - Implements the Model Context Protocol to connect LLM clients with UnifAI Network tools.
- **Dynamic tool discovery**
  - Allows LLMs to discover tools that are available on the UnifAI Network at runtime.
- **Tool search**
  - Provides search capabilities over available UnifAI tools so LLMs can find relevant functionality.
- **Tool invocation/orchestration**
  - Lets LLMs call and orchestrate tools exposed on the UnifAI Network through a unified MCP interface.
- **Multi-language SDK support (via successor projects)**
  - Functionality continued in:
    - Python MCP server implementation within `unifai-sdk-py`.
    - TypeScript MCP server implementation within `unifai-sdk-js`.

## Technology & Integration
- **Protocol**: Model Context Protocol (MCP)
- **Ecosystem**: UnifAI Network tools and services
- **Client compatibility**: For use with MCP-compatible LLM clients, via the UnifAI SDKs.

## Project Status
- Original repository indicates that UnifAI MCP servers are now part of the UnifAI SDKs, and directs users to the Python and TypeScript SDK repositories for current usage.

## Pricing
- Not specified in the available content (open-source GitHub repository; no pricing information provided).