## iTerm MCP

**Category:** MCP Server Directories & Lists  
**Repository:** https://github.com/ferrislucas/iterm-mcp  
**Brand:** iTerm2  
**Slug:** `iterm-mcp`

---

## Overview

iTerm MCP is a Model Context Protocol (MCP) server that connects to the current iTerm2 session on macOS. It lets language models safely execute, monitor, and interact with commands in your existing terminal, including REPLs, via MCP-compatible clients such as Claude Desktop.

---

## Features

- **Efficient token usage**
  - Allows the model to inspect only the relevant portion of terminal output.
  - Optimized for workflows where the model typically only needs the last few lines, even for long-running commands.

- **Natural terminal sharing and interaction**
  - Shares your active iTerm session with the model.
  - Enables asking questions about what is currently visible on the screen.
  - Supports delegating terminal tasks to the model and observing each step as it executes.

- **Full terminal control & REPL support**
  - Can start and interact with REPL environments.
  - Supports sending control characters such as `Ctrl+C`, `Ctrl+Z`, and similar.

- **Minimal dependencies & easy integration**
  - Built with a small dependency footprint.
  - Runnable via `npx`.
  - Designed to integrate easily with Claude Desktop and other MCP clients.

- **Model Context Protocol server**
  - Exposes terminal operations as MCP tools for structured, safe interaction by LLMs.

---

## Exposed Tools

- **`write_to_terminal`** – Send commands or text input to the current iTerm session.
- **`read_terminal_output`** – Read terminal output so the model can inspect recent command results.
- **`send_control_character`** – Send control characters (e.g., interrupts, suspends) to manage running processes.

---

## Requirements

- iTerm2 running on **macOS** (current session is used by the server).
- An MCP-compatible client (e.g., **Claude Desktop**).
- Ability to run the server via `npx` (Node.js environment implied).

---

## Installation / Setup

For **Claude Desktop** integration, add the server configuration to the Claude configuration file.

- **macOS config path:**
  - `~/Library/Application Support/Claude/claude_desktop_config.json`

- **Windows config path (for Claude Desktop client):**
  - `%APPDATA%/Claude/claude_desktop_config.json`

The server itself is designed to be runnable via `npx` and then referenced from your MCP client configuration.

---

## Pricing

- Pricing is **not specified** in the provided content.  
- Source code is hosted on GitHub; see the repository and `LICENSE.md` for licensing and usage terms.