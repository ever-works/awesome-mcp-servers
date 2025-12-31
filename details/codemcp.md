# codemcp

**Category:** Code-execution automation MCP servers  
**Website/Source:** https://github.com/ezyang/codemcp  
**License:** Apache-2.0

## Description
codemcp is a minimal coding-agent MCP (Model Context Protocol) server for Claude Desktop. It provides basic tools for reading and writing files and executing command-line operations, intended as a simple reference implementation of an MCP-based coding agent.

## Features
- **MCP server for coding agents**
  - Implements the Model Context Protocol to serve tools to an AI coding assistant (e.g., Claude Desktop).
- **File system operations**
  - Read files from the local file system.
  - Write or update files on disk.
- **Command-line execution**
  - Run shell/command-line operations from within the MCP environment.
- **Minimal, reference-focused design**
  - Designed as a small, understandable reference implementation rather than a full-featured automation suite.
- **Project structure and support files**
  - `codemcp/` core implementation directory.
  - `tests/` for automated testing of functionality.
  - `e2e/` end-to-end test setups.
  - `stubs/` for type or interface stubbing.
  - `static/` for any static assets used by the server or documentation.
  - Configuration files (e.g., `.editorconfig`, `.gitignore`, `.pre-commit-config.yaml`) for consistent development and contribution workflows.
- **Documentation**
  - `INSTALL.md` for installation and setup instructions.
  - `ARCHITECTURE.md` describing internal structure and design.
  - `CLAUDE.md` for Claude-specific usage and integration notes.
  - `CONTRIBUTING.md` guidelines for contributors.

## Pricing
codemcp is an open-source project under the Apache-2.0 license. No paid plans or pricing tiers are listed.