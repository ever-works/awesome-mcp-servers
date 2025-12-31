# server-memory

An official Model Context Protocol (MCP) server that provides a knowledge-graph–based persistent memory system for AI agents.

## Overview

- **Type:** MCP server (AI integration)
- **Purpose:** Persistent memory and knowledge graph management for AI agents and tools
- **Repository:** `modelcontextprotocol/servers` → `src/memory`
- **Category:** ai-integration-mcp-servers
- **Tags:** memory, knowledge-graph, ai-integration

## Features

> Note: The repository listing shows this as the `memory` server within the MCP servers collection and indicates recent refactors, but the detailed README content isn’t visible in the provided excerpt. The features below are therefore limited to what can be reliably inferred from the structure and commit messages.

- **Knowledge-graph–based memory model**  
  Designed to store information as entities and relations (knowledge graph structure) rather than flat text, enabling richer, structured memory for AI agents.

- **Persistent memory for AI agents**  
  Acts as a long-term memory backend that can be queried and updated across sessions, allowing agents to retain context over time.

- **MCP-compliant server implementation**  
  Implemented as an official MCP server within the `modelcontextprotocol/servers` monorepo for standardized integration with MCP-compatible clients.

- **Modern TypeScript SDK usage**  
  Uses the modern `McpServer` API from `@modelcontextprotocol/sdk/server/mcp.js`, replacing older low-level server APIs.

- **Tool-based API (9 tools)**  
  Exposes its capabilities as MCP tools using `registerTool()`. There are 9 tools (per commit message) that likely cover operations such as creating, updating, querying, and deleting entities and relations in the memory graph.

- **Zod-based schemas for safety and validation**  
  - Reusable Zod schemas defined for **Entity** and **Relation** types.  
  - Zod schemas used directly for `inputSchema` and `outputSchema` for each tool, providing structured, validated I/O.

- **Structured content responses**  
  All tool responses include `structuredContent`, enabling clients to consume rich, typed outputs instead of only raw text.

- **Dockerized deployment**  
  Includes a `Dockerfile` for containerized deployment, making it easier to run the memory server in various environments.

- **Automated testing**  
  - `__tests__` directory with tests implemented using the Vitest testing framework.  
  - Tests cover memory management features, increasing reliability of entity/relation operations.

- **Part of the official MCP servers collection**  
  Lives in the main `modelcontextprotocol/servers` repository alongside other official servers (e.g., filesystem, slack, postgres), implying it follows shared conventions and integration patterns.

## Integration & Usage

- **Intended clients:** Any MCP-capable client (e.g., tools or editors that support MCP) can connect to this server to provide persistent, knowledge-graph memory to AI agents.
- **Tech stack:** TypeScript, `@modelcontextprotocol/sdk`, Zod, Vitest, Docker.

*(For exact tool names, parameters, and example requests/responses, consult `src/memory/README.md` and `index.ts` in the repository, which are not fully included in the provided content.)*

## Pricing

- Not specified in the provided content. This appears to be an open-source server within the `modelcontextprotocol/servers` GitHub repository; no pricing information is available here.