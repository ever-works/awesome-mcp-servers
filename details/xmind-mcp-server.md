# XMind MCP Server

## Description
A Model Context Protocol (MCP) server for analyzing and querying XMind mind map files. It allows LLMs and MCP-compatible clients (such as Claude Desktop) to read, search, and extract information from directories of XMind-based knowledge structures.

## Features
- **XMind mind map analysis and querying**  
  - Works with XMind `.xmind` files as structured knowledge sources.
- **Directory-level operations**  
  - `list_xmind_directory`: list XMind files within a directory so clients can discover available maps.
- **File reading and aggregation**  
  - `read_xmind`: read and parse a single XMind file.  
  - `read_multiple_xmind_files`: load and analyze multiple XMind files in one request.
- **Task and TODO extraction**  
  - `get_todo_tasks`: extract tasks or TODO-style items from XMind maps.
- **Search capabilities**  
  - `search_xmind_files`: search across XMind files for matching content.  
  - `search_nodes`: search within nodes of a map for specific text or criteria.
- **Node-level extraction**  
  - `extract_node`: extract a specific node and its content from a map.  
  - `extract_node_by_id`: retrieve a node by its internal ID, enabling precise programmatic access.
- **MCP integration**  
  - Exposes the above operations as MCP tools, so LLMs can programmatically browse, query, and analyze XMind-based knowledge during a conversation.

## Installation
- **Via Smithery**: can be installed for Claude Desktop using Smithery (`smithery.ai`) as an MCP server.  
- **Manual installation**: supports manual setup (e.g., via Node.js/TypeScript environment) as described in the project’s README.

## Usage
- Run as an MCP server and register it in `claude_desktop_config.json` for either development or production setups.
- Provides tools (`read_xmind`, `search_xmind_files`, `extract_node`, etc.) that can be invoked from MCP-compatible clients.

## Technical Details
- Implemented in **TypeScript** (see `index.ts`, `tsconfig.json`, `package.json`).
- Distributed as a GitHub repository (`apeyroux/mcp-xmind`).

## Pricing
- Pricing is **not specified** in the available content. The project is distributed as an open-source GitHub repository; refer to the repository for license and usage terms.