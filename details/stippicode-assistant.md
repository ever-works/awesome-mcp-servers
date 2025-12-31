# stippi/code-assistant

**Category:** Code Execution & Automation MCP Servers  
**Tags:** code-execution, development, assistant  
**Source:** https://github.com/stippi/code-assistant

## Overview
Code Assistant is an AI-powered, autonomous coding assistant written in Rust. It provides both command-line and graphical interfaces for analyzing, modifying, and generating code. It also exposes an MCP (Model Context Protocol) server (and ACP mode) so other LLM-based tools can use its capabilities for general-purpose coding assistance across multiple environments.

## Features
- **Autonomous coding assistant**
  - An LLM-driven agent that can plan and perform multi-step coding tasks.
  - Focused on autonomous code analysis and modification workflows.

- **MCP and ACP modes**
  - Provides an MCP server for integration with MCP-compatible clients.
  - Includes an ACP mode (agent control protocol / similar auxiliary mode) for extended agent-based workflows.
  - Designed as a general-purpose coding agent that other tools can orchestrate.

- **Multi-environment support**
  - Can operate across multiple development environments (e.g., different projects or systems) via its server-based architecture.

- **File and project operations**
  - List files in a project or workspace.
  - Read file contents for analysis.
  - Replace content within files.
  - Write or create files programmatically.

- **Command execution**
  - Execute shell or system commands from within the assistant.
  - Useful for running builds, tests, linters, or other dev tooling during autonomous workflows.

- **Web search integration**
  - Perform web searches as part of coding tasks.
  - Enables the assistant to pull in documentation or external references when needed.

- **Interfaces**
  - **Command-line interface (CLI):** text-based interaction for developers in the terminal.
  - **Graphical interface (GUI):** more visual interaction mode for managing and reviewing code changes.

- **Configuration examples**
  - Example model configuration file: `models.example.json`.
  - Example provider configuration file: `providers.example.json`.
  - Example tools configuration file: `tools.example.json`.

- **Agent configuration docs**
  - `AGENTS.md` outlines available agents / agent setup (e.g., different behaviors or roles) for customizing how the assistant operates.

- **Rust-based implementation**
  - Implemented in Rust with a Cargo workspace (`Cargo.toml`, `crates/`).
  - Includes CI configuration for automated builds.

## Pricing
No pricing information is provided in the available content. The project appears to be an open-source GitHub repository; check the repository and `LICENSE` file for usage terms and any licensing constraints.
