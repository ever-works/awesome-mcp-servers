# MCP Create

A dynamic MCP server management service that can create, run, and manage Model Context Protocol (MCP) servers on demand. The service itself runs as an MCP server and orchestrates other MCP servers as child processes.

---

## Features

- **Dynamic MCP server lifecycle management**
  - Create MCP servers dynamically at runtime
  - Run MCP servers as child processes
  - Manage multiple MCP servers from a single controller MCP server

- **Execution environment**
  - Currently supports **TypeScript** MCP server code
  - Planned future support for **JavaScript** and **Python** MCP servers

- **Tool routing and execution**
  - Execute tools exposed by child MCP servers via the main MCP Create server

- **Code management**
  - Update existing MCP server code
  - Restart servers after code changes

- **Cleanup and removal**
  - Remove and shut down unnecessary or obsolete MCP servers

- **Deployment options**
  - Docker-based deployment (recommended)
  - Manual TypeScript-based setup

---

## Technical

- License: MIT
- Implementation: TypeScript
- Distribution: Docker image or manual Node/TypeScript install

---

## Pricing

- Not specified / Open-source (MIT-licensed).