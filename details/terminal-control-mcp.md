# Terminal Control MCP

A Model Context Protocol (MCP) server that enables secure terminal command execution, directory navigation, and filesystem operations through a standardized interface.

## Overview
- **Type:** MCP server (code-execution / automation)
- **Repository:** https://github.com/GongRzhe/terminal-controller-mcp
- **Category:** Code Execution & Automation MCP Servers
- **Tags:** command-execution, automation, shell

## Features
- **Secure terminal command execution** via MCP
- **Directory navigation** (changing and inspecting current working directories)
- **File system operations** through MCP (e.g., listing directories, interacting with files)
- **Standardized MCP interface** for tool integration with LLM clients or MCP-compatible runtimes
- **Configuration files included**:
  - `mcp-config.json` for MCP server configuration
  - `smithery.yaml` for integration/build tooling
- **Containerization support** via `Dockerfile` for running the server in a controlled environment
- **Python-based implementation**:
  - Uses `pyproject.toml` and `requirements.txt` for dependency and project management
  - `.python-version` to pin Python runtime version
- **Automation & CI hooks** via `.github/workflows` (for automated checks or builds)

## Installation & Integration
- Install and run as an MCP server from the GitHub repository.
- Configurable through `mcp-config.json` for integration with MCP-compatible clients.
- Can be built and run via the provided `Dockerfile` for isolated execution.

## Licensing
- A `LICENSE` file is present in the repository (see GitHub for exact license terms).

## Pricing
- Not specified; open-source repository on GitHub (refer to license for usage terms).