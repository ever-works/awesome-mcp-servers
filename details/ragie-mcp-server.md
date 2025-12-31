# Ragie MCP Server

## Overview
Ragie MCP Server is a Model Context Protocol (MCP) server that exposes Ragie’s knowledge base retrieval capabilities to MCP-compatible AI agents. It provides a single tool to query a Ragie RAG knowledge base, enabling retrieval of relevant context from enterprise data sources.

## Features
- **Model Context Protocol implementation**: Acts as an MCP-compliant server that communicates over stdio using MCP protocol messages.
- **Knowledge base retrieval**: Connects to a Ragie knowledge base and retrieves relevant information for AI models.
- **Single `retrieve` tool**:
  - Exposes a `retrieve` tool within MCP.
  - Allows querying the Ragie knowledge base for contextual documents or information.
- **Ragie API integration**:
  - Uses Ragie’s API for all retrieval operations.
  - Authenticated access via API key.
- **Node.js-based server**:
  - Implemented for Node.js 18 or later.
  - Distributed as an npm package runnable via `npx`.
- **STDIO-based server mode**:
  - Starts a process that listens on standard input/output for MCP messages.

> Note: While Ragie as a platform integrates data sources such as Google Drive, Notion, and JIRA, this repository specifically focuses on exposing retrieval from the configured Ragie knowledge base via MCP.

## Technical Requirements
- **Runtime**: Node.js >= 18
- **Environment variable**:
  - `RAGIE_API_KEY` (required) – Ragie API authentication key

## Usage
Run the MCP server via `npx`:
```bash
RAGIE_API_KEY=your_api_key npx @ragieai/mcp-server
```
The server will start and listen on stdio for MCP protocol messages and provide the `retrieve` tool to connected MCP clients.

## Licensing
- Licensed under the **MIT License**.