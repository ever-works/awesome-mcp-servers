# deepseek-thinker-mcp

**Category:** ai-integration-mcp-servers  
**Brand:** deepseek  
**Repository:** https://github.com/ruixingshi/deepseek-thinker-mcp

## Overview

`deepseek-thinker-mcp` is a Model Context Protocol (MCP) server that exposes DeepSeek’s reasoning / chain-of-thought content to MCP-enabled AI clients (such as Claude Desktop). It can connect either to the official DeepSeek API service or to a locally hosted DeepSeek model via Ollama.

## Features

- **MCP provider for reasoning content**  
  - Implements an MCP server that supplies DeepSeek’s reasoning / chain-of-thought (CoT) content.  
  - Designed to work with MCP-compatible clients (e.g., Claude Desktop).

- **Multiple backend options**  
  - Supports connecting to the hosted DeepSeek API service.  
  - Supports using a local Ollama server running a DeepSeek model.

- **DeepSeek CoT exposure**  
  - Makes DeepSeek’s internal thought processes accessible through MCP, enabling tools and clients to consume structured reasoning traces.

- **Containerization & deployment**  
  - Includes a `Dockerfile` for containerized deployment of the MCP server.

- **Node.js / TypeScript implementation**  
  - Distributed as an npm-based project (`package.json`, `package-lock.json`).  
  - TypeScript configuration via `tsconfig.json`.

- **Smithery integration metadata**  
  - Contains `smithery.yaml`, indicating configuration for MCP/tooling registries or automation around MCP servers.

## Pricing

- Not specified in the available content. The project is hosted publicly on GitHub; licensing and any pricing details (if applicable) should be checked directly in the repository.