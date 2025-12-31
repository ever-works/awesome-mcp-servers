# voicemode

**Category:** Media Processing MCP Servers  
**Vendor/Author:** mbailey  
**License:** MIT  
**Source:** https://github.com/mbailey/voicemode  
**Website:** https://getvoicemode.com/

## Overview
VoiceMode is an MCP (Model Context Protocol) server that adds full voice interaction capabilities to LLM-based assistants, including Claude Code. It provides speech-to-text, text-to-speech, and real-time conversational audio, enabling natural, spoken interactions instead of purely text-based chats.

## Features
- **MCP Server for Voice**
  - Implements a complete voice-focused MCP server compatible with LLM-based assistants.
  - Designed to integrate directly with Claude Code.

- **Speech-to-Text (STT)**
  - Converts spoken audio input into text messages the assistant can process.

- **Text-to-Speech (TTS)**
  - Converts LLM text responses back into spoken audio output.

- **Real-Time Voice Conversations**
  - Supports interactive, back-and-forth voice conversations with low friction compared to manual audio uploads.

- **Claude/Claude Code Integration**
  - Includes plugin/configuration files (e.g., `.claude-plugin`, `.claude`) indicating a direct integration path for Claude Code environments.

- **CLI / Scripts and Installer**
  - `bin/`, `scripts/`, and `installer/` directories suggest command-line utilities and installation helpers for running and configuring the server.

- **Documentation & Examples**
  - `docs/` and `tests/` directories indicate available documentation and test coverage for setup, usage, and validation.

- **Vendor & Dependency Management**
  - `vendor/` tree suggests vendored dependencies or libraries bundled for easier installation.

> Note: The GitHub content excerpt does not expose detailed configuration, supported platforms, or specific STT/TTS engines. Those details would be available in the full README/docs on the repository or project website.

## Technical Details
- **Protocol:** MCP (Model Context Protocol) server
- **Intended clients:** LLM-based assistants (explicitly Claude Code; others that support MCP may also integrate)
- **Repository structure highlights:**
  - `voice_mode/` – core server implementation
  - `.claude-plugin/`, `.claude/` – Claude-specific integration assets
  - `tests/` – automated tests

## Pricing
No pricing information is provided in the extracted content. The project is open source under the MIT license; any commercial/hosted offerings (if they exist) are not described in the available text.