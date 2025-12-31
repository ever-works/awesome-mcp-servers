# ssh-mcp

**Category:** Server Management Tools  
**Website/Source:** https://github.com/tufantunc/ssh-mcp  
**License:** MIT  
**Developer/Brand:** tufantunc

## Overview
ssh-mcp is an open-source MCP (Model Context Protocol) server that exposes SSH control for servers. It enables secure remote command execution and server management over SSH, integrating SSH-based operations into MCP-compatible clients and workflows.

## Features
- **MCP server implementation** for integrating SSH operations via the Model Context Protocol.
- **SSH control for servers**, designed primarily for Linux servers (Windows support mentioned at a higher level, but core repo description focuses on Linux).
- **Remote command execution** over SSH, suitable for automating administrative and management tasks.
- **Server management capabilities** exposed through MCP, allowing tooling/agents that support MCP to orchestrate SSH operations.
- **Containerized deployment option** via provided `docker-compose.yml` for easier setup and running of the MCP server.
- **TypeScript/Node.js codebase**, with configuration via `package.json` and `tsconfig.json`.
- **Testing setup** in the `test` directory for validating functionality.

## Pricing
- ssh-mcp is open-source software released under the MIT license and is free to use, modify, and distribute.
