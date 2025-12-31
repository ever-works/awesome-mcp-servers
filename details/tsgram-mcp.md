# tsgram-mcp

**Website:** https://github.com/areweai/tsgram-mcp  
**Category:** Messaging MCP Servers  
**Tags:** telegram, messaging, workspace-access

## Overview
TSgram MCP is a Telegram-focused Model Context Protocol (MCP) server that connects Telegram with Claude and local workspace access on your phone using TypeScript. It enables code reading and writing through MCP tools directly from Telegram chats.

## Features
- **Telegram integration**
  - Acts as a Telegram MCP server for interacting via Telegram bots/chats.
  - Designed for using Claude through Telegram as a client interface.

- **Code and workspace interaction**
  - Provides MCP tools for reading and writing code.
  - Enables interaction with a local workspace (e.g., files and project structure) from a mobile device.
  - Intended for “on-the-go” code exploration and debugging.

- **TypeScript-based implementation**
  - Implemented in TypeScript (see `src` directory).
  - Includes configuration and tooling typical for a TypeScript project (`.eslintrc.js`, tests, etc.).

- **Configuration and examples**
  - Example configuration files in `config-examples/`.
  - `.env.example` for environment variable setup.
  - `.mcp.json` for MCP server configuration.

- **Docker support**
  - Multiple Dockerfiles for different setups:
    - `Dockerfile` (default image)
    - `Dockerfile.local` (local development)
    - `Dockerfile.remote` (remote deployment)
    - `Dockerfile.workspace` and `Dockerfile.tsgram-workspace` (workspace-focused images)
  - `docker/` directory with additional docker-related assets.

- **Project assets and docs**
  - `docs/` directory for additional documentation.
  - `assets/` directory for project-related resources.
  - `scripts/` for automation and helper scripts.

- **Queues and data handling**
  - `.telegram-queue/` directory suggesting queued handling of Telegram updates/messages.
  - `data/` directory for runtime or configuration data storage.

- **Claude-specific configuration**
  - `.claude/` directory and `CLAUDE.md` for Claude integration details and instructions.

- **Testing and quality**
  - `tests/` directory for automated tests.
  - ESLint configuration for code quality.

- **Open-source licensing**
  - Distributed under an OSI license (see `LICENSE` file in repository).

## Pricing
- Not specified in the available content. The project appears to be an open-source GitHub repository; consult the repository README and LICENSE for usage and any associated costs.
