# mindmap-mcp-server

**Category:** Data Visualization  
**Brand:** yuchenssr  
**Source:** https://github.com/YuChenSSR/mindmap-mcp-server  
**License:** MIT

## Description
mindmap-mcp-server is a Model Context Protocol (MCP) server that converts structured Markdown content into interactive mind maps. It is designed to enable AI agents and tools to visualize and explore content as mind maps.

## Features
- **MCP server implementation**
  - Implements a Model Context Protocol server to be used by compatible AI agents and tools.
- **Markdown to mind map conversion**
  - Parses Markdown content and transforms it into mind map structures.
  - Supports visualization of structured content as nodes and relationships.
- **Interactive mind maps**
  - Generates mind maps intended for interactive exploration (e.g., pan, zoom, expand/collapse via compatible viewers or agents).
- **AI integration focus**
  - Designed to be called by AI assistants/agents to generate visual representations of content.
- **Multiple installation options**
  - Installable as a Python package via `pip`.
  - Runnable via `uvx`.
  - Docker image support for containerized and OS-agnostic usage.
- **Cross‑platform notes**
  - Installation methods tested on macOS and Linux.
  - For Windows, Docker is recommended when `npx`-based workflows cause issues.
- **Ecosystem compatibility hints**
  - Can be used as an alternative or complement to tools like the Markmap VS Code extension for mind-map-style visualization of Markdown.

## Installation
- **Via pip**
  ```bash
  pip install mindmap-mcp-server
  ```
- **Via uvx**
  ```bash
  uvx mindmap-mcp-server
  ```
- **Via Docker**
  - Supported; recommended especially for Windows users or when local toolchains cause issues.

## Pricing
- Open-source project under the MIT License.  
- No paid plans mentioned in the provided content.