---
title: GhidrAssistMCP
slug: ghidrassistmcp
brand: Ghidra
category: testing-debugging-tools
tags:
  - reverse-engineering
  - binary-analysis
  - ghidra
source_url: https://github.com/jtang613/GhidrAssistMCP
images:
  - https://opengraph.githubassets.com/1/jtang613/GhidrAssistMCP
featured: false
license: MIT
---

## Description

GhidrAssistMCP is a Ghidra extension that exposes a native MCP (Model Context Protocol) server, allowing AI assistants and other external tools to interact programmatically with Ghidra’s reverse‑engineering environment. It is designed to let LLMs and automation workflows analyze binaries via Ghidra through a standardized API, with GUI-based configuration and integrated logging.

## Features

- **MCP server for Ghidra**
  - Implements a Model Context Protocol server directly inside Ghidra.
  - Allows external AI agents and tools to access Ghidra functionality via a standard protocol.

- **LLM and tool integration**
  - Provides a large set of tools for LLMs to interact with loaded binaries.
  - Supports AI-driven analysis workflows within Ghidra projects.

- **Binary analysis and reverse engineering support**
  - Operates on Ghidra’s decompilation and disassembly data.
  - Enables scripted or AI-assisted exploration of functions, symbols, and program structures (inferred from being a Ghidra extension for reverse engineering).

- **GUI configuration**
  - Includes graphical configuration options inside Ghidra for setting up and managing the MCP server.

- **Logging**
  - Built-in logging for server activity and tool usage.
  - Facilitates debugging and auditing of AI/tool interactions with Ghidra.

- **Ghidra extension packaging**
  - Distributed as a standard Ghidra extension (with `Module.manifest` and `extension.properties`).
  - Integrates into Ghidra’s extension and build system (Gradle-based build).

## Pricing

- Not specified (open-source MIT-licensed project; no pricing information provided in the source content).
