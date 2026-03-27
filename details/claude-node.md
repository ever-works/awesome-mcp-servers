# claw-army/claude-node

**Category:** AI Integration – MCP Servers
**Brand:** claw-army
**Source:** https://github.com/claw-army/claude-node
**License:** MIT

## Overview
claude-node is a Python library that provides a subprocess bridge for Claude Code CLI, giving Python code direct access to Claude Code native capabilities via stream-json. It enables Python applications to leverage Claude Code's capabilities as a subprocess.

## Features
- **Python subprocess bridge for Claude Code CLI**
  - Enables direct communication between Python code and Claude Code via stdin/stdout.

- **stream-json protocol**
  - Uses stream-json for efficient JSON streaming communication with Claude Code subprocess.

- **Native Claude Code integration**
  - Provides Python code access to Claude Code capabilities without API keys or external services.

- **ClaudeController class**
  - Main interface for spawning and communicating with Claude Code subprocess.

- **Session reuse**
  - Designed to reuse a single healthy controller instance rather than creating new subprocesses.

## Pricing
- Open source and free to use under MIT license.