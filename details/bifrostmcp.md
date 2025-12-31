# BifrostMCP

**Category:** Development Tools – MCP Servers  
**Brand:** biegehydra  
**License:** AGPL-3.0  
**Source Code:** https://github.com/biegehydra/BifrostMCP

## Overview
BifrostMCP is a Visual Studio Code extension that runs a Model Context Protocol (MCP) server to expose semantic IDE capabilities—such as "Find Usages" and "Rename"—to AI agents and LLM-based tools. It acts as a bridge between VS Code’s language/intellisense features and agents that communicate over MCP.

## Features
- **VS Code Extension**  
  - Distributed as a VS Code extension integrating directly with the editor environment.  
  - Uses VS Code’s language and semantic tooling APIs.

- **MCP Server Integration**  
  - Implements a Model Context Protocol server inside VS Code.  
  - Allows AI agents and tools that speak MCP to connect to an active VS Code workspace.

- **Semantic IDE Tools Exposure**  
  - Exposes VS Code semantic features to LLMs/agents, including:  
    - **Find Usages** – query where a symbol is used across a project.  
    - **Rename** – trigger symbol renames via the MCP interface.  
  - Designed to make IDE-grade refactoring and navigation features accessible programmatically.

- **Project Configuration Support**  
  - Example configuration file: `example.bifrost.config.json`.  
  - Supports custom configuration for how the MCP server behaves or integrates with projects (details in repo config/example files).

- **Cursor / Agent Rules Example**  
  - `ExampleCursorRules.md` provides example rules or guidance for using BifrostMCP with cursor/agent-style workflows.

- **Development & Testing Setup**  
  - Includes VS Code-specific project configuration in `.vscode/`.  
  - `.vscodeignore` for packaging the extension.  
  - `.vscode-test.mjs` for automated or integration testing of the extension.  
  - ESLint configuration via `eslint.config.mjs` for consistent code quality.

- **Changelog and Versioning**  
  - `CHANGELOG.md` tracks updates and changes across versions.

## Pricing
BifrostMCP is an open-source project under the AGPL-3.0 license. No paid plans are listed in the repository.

## Tags
- ide  
- vscode  
- developer-tools
