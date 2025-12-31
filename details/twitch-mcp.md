# twitch-mcp

**Category:** Messaging MCP Servers  
**Tags:** twitch, streaming, automation  
**Source:** https://github.com/Eclipse-XV/twitch-mcp

## Overview

twitch-mcp is an open-source Model Context Protocol (MCP) server that connects MCP-compatible clients (such as Claude, Gemini CLI, Qwen Coder, and similar coding/chat assistants) directly to Twitch chat. It is designed to help streamers automate moderation, manage streams, and enhance chat engagement using AI tools.

## Features

- **MCP Server for Twitch**
  - Implements a Model Context Protocol (MCP) server that exposes Twitch functionality to MCP clients.
  - Allows tools like Claude and other MCP-compatible assistants to interact with Twitch in a structured way.

- **Twitch Chat Integration**
  - Connects directly to Twitch chat from an MCP client.
  - Enables AI assistants to read and respond to chat messages programmatically (subject to the tools exposed by the server).

- **AI-Powered Stream Tools**
  - Provides AI-driven capabilities for Twitch streamers via MCP.
  - Focuses on automating and assisting with common stream tasks.

- **Moderation Support**
  - Intended for chat moderation workflows (e.g., monitoring messages, assisting with moderation decisions via MCP tools).

- **Stream Management**
  - Supports stream management tasks through AI assistants (e.g., controlling or interacting with aspects of the stream exposed via the server’s tools).

- **Engagement & Interactivity**
  - Built to enhance chat engagement by letting AI tools participate in or manage interactive elements.
  - Description indicates support for:
    - Automating channel point predictions.
    - Triggering stream events.
    - Extending interactive chat functionality (e.g., custom commands or reactions via MCP tools).

- **Client Compatibility**
  - Works with multiple MCP-compatible clients, including but not limited to:
    - Claude Code / Claude desktop MCP client
    - Gemini CLI
    - Qwen Coder
    - Other MCP-aware tools that can connect to MCP servers.

- **Quick Start (No Cloning Required)**
  - Offers a quick start workflow that does not require cloning the repository (e.g., likely via Docker image or prebuilt distribution), enabling fast setup from an MCP client configuration.

- **Multi-language / Multi-environment Layout**
  - Repository includes:
    - `twitch-mcp-npm` (suggesting an NPM-distributed package or client tooling).
    - Java/Maven project structure (`pom.xml`, `java/`, `src/main/`), indicating a Java-based server implementation.
    - Scripts directory (`scripts/`) for helper tooling and automation.

- **Change Tracking & Developer Docs**
  - `CHANGELOG.md` for version and feature change tracking.
  - `README-developers.md` and `CLAUDE.md` for developer-focused documentation and configuration specifics (e.g., how to wire into Claude or other MCP clients).

## Pricing

- The project is hosted on GitHub and presented as an open-source repository.
- No pricing information or paid plans are specified in the available content.