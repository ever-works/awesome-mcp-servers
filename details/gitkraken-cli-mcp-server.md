# GitKraken CLI MCP Server

## Overview
The GitKraken CLI MCP Server is a local MCP (Model Context Protocol) server exposed via the `gk` command-line tool. It wraps GitKraken APIs and common developer services so MCP-compatible agents (LLMs and tools) can interact programmatically with Git repositories, pull requests, and related work items.

It runs on macOS, Windows, and Unix systems.

## Features
- **Local MCP server**  
  - Runs as a local MCP server process for integration with MCP-compatible AI agents.

- **Git integration**  
  - Wraps core `git` operations so LLMs can interact with repositories via MCP tools.  
  - Supports working with multiple repositories at once, giving a “monorepo-like” workflow across projects.

- **GitKraken API integration**  
  - Exposes GitKraken-specific APIs and functionality to MCP clients.  
  - Provides tools for interacting with GitKraken Work Items (features, issues, or tasks associated with your work).

- **Issue & project tracking integration**  
  - Jira MCP actions are wrapped and exposed as tools, allowing agents to work with Jira issues through the MCP server.

- **Git hosting & PR workflows**  
  - GitHub-related actions (e.g., pull requests) are exposed as tools for AI agents to consume.  
  - Enables programmatic interaction with pull requests and repository hosting workflows.

- **AI-assisted workflows (via GitKraken CLI)**  
  - AI-powered commit message generation.  
  - AI-powered pull request generation.  
  - These capabilities are accessible through the CLI and can be surfaced to LLMs via the MCP tools.

- **Work Items–centric UX**  
  - Core concept built around “Work Items” (the feature or issue being tackled).  
  - Designed to coordinate work across multiple repositories as if they were a single monorepo.

- **Cross-platform availability**  
  - Supports macOS, Windows, and Unix environments.

- **Configurable per AI application**  
  - Installation and configuration instructions are available for specific AI tools/clients (see GitKraken Help Center).

## Installation
Installation is performed through the GitKraken CLI (`gk`). Platform-specific and AI-tool–specific instructions are documented in the GitKraken Help Center:
- https://help.gitkraken.com/cli/gk-cli-mcp/

## Pricing
No pricing information is provided in the referenced content. (Consult the main GitKraken website or documentation for licensing and pricing details.)

## Links
- Repository & releases: https://github.com/gitkraken/gk-cli  
- MCP server documentation: https://help.gitkraken.com/cli/gk-cli-mcp/  
- Introduction article: (linked from README) GitKraken blog introduction to the MCP server