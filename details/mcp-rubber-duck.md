# mcp-rubber-duck

**Category:** Testing & Debugging Tools  
**Tags:** debugging, openai, ai-assistant  
**Source:** https://github.com/nesquikm/mcp-rubber-duck  
**License:** MIT

## Overview
mcp-rubber-duck is an MCP (Model Context Protocol) server that bridges multiple OpenAI-compatible LLMs into a single "rubber duck" debugging panel. It is designed to be used by coding assistants to explain, discuss, and reason about code, while giving the connected models access to MCP tools.

## Features
- **MCP server implementation**
  - Runs as an MCP server that can be connected to compatible clients and coding assistants.
  - Exposes functionality through MCP tools so LLM-based coding assistants can call it programmatically.

- **Bridge to multiple OpenAI-compatible LLMs**
  - Connects to multiple OpenAI-compatible large language models.
  - Allows querying different models from a single MCP endpoint.
  - Supports selecting between various "AI ducks" to get diverse responses and perspectives.

- **Rubber duck–style debugging**
  - Provides an AI "rubber duck" panel for explaining problems, code, and design decisions.
  - Enables conversational explanation and discussion about code issues, bugs, or refactors.
  - Focuses on code reasoning and debugging workflows rather than generic chat.

- **Tool-access for LLMs via MCP**
  - Gives the connected LLMs access to MCP tools (e.g., file access, commands, or other MCP-provided capabilities, depending on client setup).
  - Enables the AI "ducks" to research, inspect context, and act with richer environment access than plain chat.

- **Configurable environment**
  - Repository includes configuration files under a `config` directory.
  - Example environment files (e.g., `.env.example`, `.env.desktop.example`) indicate support for environment-based configuration (API keys, endpoints, etc.).

- **Deployment and integration assets**
  - Contains a `systemd` directory suggesting systemd service/unit files for running as a background service.
  - Includes `scripts` directory for helper scripts (setup, running, or auxiliary tasks).
  - `assets` directory for static or UI-related assets used by the panel or documentation.

- **Testing and quality**
  - `tests` directory indicating automated tests for core functionality.

- **Docker and environment support**
  - `.dockerignore` present, indicating Docker-based workflows are supported or planned.

## Use Cases
- Enhance coding assistants with a dedicated debugging backend that can:
  - Explain and reason about existing code.
  - Compare answers from multiple LLMs.
  - Use MCP tools to inspect or manipulate project context.

## Pricing
mcp-rubber-duck is an open-source project under the MIT license.  
No paid pricing plans are listed in the provided content.