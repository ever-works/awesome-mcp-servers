# mcp-guardian

- **Category:** MCP middleware / orchestration
- **Brand:** eqty-lab  
- **Website:** https://mcp-guardian.org  
- **Source Code:** https://github.com/eqtylab/mcp-guardian
- **Type:** GUI application and proxy toolset for managing and controlling MCP servers
- **Slug:** `mcp-guardian`
- **Tags:** proxy, gateway, orchestration

---

## Overview

mcp-guardian is a graphical management and proxy tool for MCP servers that sits between an LLM assistant and its MCP tools. It provides realtime visibility and control over all MCP server activity, and simplifies working with multiple MCP server configurations.

---

## Features

### LLM Activity Control & Monitoring
- **Message logging:**
  - Logs and displays traces of all MCP server activity initiated by an LLM assistant.
  - Enables inspection of individual tool calls and message flows.

- **Message approvals:**
  - Approve or deny individual tool call messages in real time.
  - Provides a human-in-the-loop control layer over what the LLM is allowed to execute.

- **Automated message scans (planned):**
  - Realtime automated checks for safety, privacy, and related policies (marked as “Coming Soon”).

### MCP Server & Configuration Management
- **Multiple MCP server configurations:**
  - Manage multiple MCP server setups from a single interface.
  - Quickly switch between different server collections.

- **Configuration switching:**
  - Swap active server collections without manually editing configuration files in MCP host applications.

### Proxy Tooling
- **Proxy binary:**
  - Provides `mcp-guardian-proxy` for routing and supervising traffic between LLM assistants and MCP servers.

### Development & Build Tooling
- **Cross-platform development setup:**
  - Nix-based development environment for Linux and macOS.
  - Documented build steps for Windows using Rust, Node.js, Yarn, and Just.

- **Command recipes (Justfile):**
  - `build`, `build-release` – compile the project.
  - `clean` – clean build artifacts.
  - `fmt`, `fmt-check` – format and check formatting.
  - `lint` – run linters.
  - `test` – run tests.
  - `readme-check`, `readme-update` – verify or regenerate README.
  - `do`, `do-all` – helper commands to run recipes in specific directories.

---

## Platforms & Development

- **Supported development environments:**
  - Linux (via Nix dev shell)
  - macOS (via Nix dev shell)
  - Windows (Git + Rust + Node.js + Yarn + Visual Studio C++ toolchain)

- **Key tooling:** Nix, Rust, Node.js, Yarn, Just

---

## Pricing

No pricing information is provided in the available content. The project appears to be open source, but users should check the repository or website for licensing and any commercial terms.
