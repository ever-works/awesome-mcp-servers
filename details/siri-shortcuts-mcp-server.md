# Siri Shortcuts MCP Server

## Overview
Siri Shortcuts MCP Server is an open-source Model Context Protocol (MCP) server that exposes macOS Siri Shortcuts as tools for LLMs. It enables programmatic listing, opening, and execution of shortcuts from the macOS Shortcuts app.

- **Category:** Workflow Automation MCP Servers  
- **Brand / Platform:** Apple (macOS Siri Shortcuts)  
- **Source Code:** https://github.com/dvcrn/mcp-server-siri-shortcuts  
- **Slug:** `siri-shortcuts-mcp-server`  
- **Tags:** automation, apple, task-automation

## Features
- **MCP integration**  
  - Implements a Model Context Protocol (MCP) server interface.  
  - Exposes Siri Shortcuts as callable tools for LLM-based clients.

- **Shortcut discovery & management**  
  - List available Siri Shortcuts from the macOS Shortcuts app.  
  - Access metadata via MCP tools (inferred from listing capability).

- **Shortcut execution**  
  - Run existing Siri Shortcuts programmatically through MCP.  
  - Open specific shortcuts from the Shortcuts app via MCP commands.

- **macOS Shortcuts integration**  
  - Integrates directly with the native macOS Shortcuts app.  
  - Designed for Apple ecosystem workflows and automation.

- **Developer tooling**  
  - TypeScript-based implementation (`index.ts`, `shortcuts.ts`, `sse.ts`).  
  - Test suite using Vitest (`shortcuts.test.ts`, `vitest.config.ts`).  
  - Configuration via `tsconfig.json` and `package.json`.  
  - Dockerfile included for containerized deployment.

- **Open source licensing**  
  - Distributed with an open-source license (`LICENSE` in repository).

## Pricing
- **License / Cost:** Open-source project; no pricing information or paid plans are specified in the repository content.
