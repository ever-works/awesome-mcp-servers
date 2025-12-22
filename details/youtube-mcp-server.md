# YouTube MCP Server

**Category:** MCP server directories & lists  
**Type:** Open-source MCP server for YouTube API  
**Source:** <https://github.com/ZubeidHendricks/youtube-mcp-server>

## Overview

YouTube MCP Server is a Model Context Protocol (MCP) server that exposes YouTube API functionality to LLM-driven tools. It focuses on video lifecycle management, Shorts creation, and access to YouTube analytics from within MCP-compatible clients.

## Features

- **YouTube API integration**
  - Connects to the official YouTube API
  - Designed to be accessed through MCP-compatible LLM tools

- **Video management**
  - General video management capabilities (as exposed via YouTube API)
  - Intended for managing channel video content from within an LLM environment

- **Shorts creation**
  - Supports creation of YouTube Shorts via the YouTube API

- **Analytics access**
  - Access to YouTube analytics data
  - Oriented toward “advanced analytics” use cases (as supported by the underlying YouTube API)

- **MCP server implementation details**
  - Ships with an example MCP configuration file: `.mcp.json.example`
  - Uses environment-based configuration via `.env.example`
  - Containerization support via `Dockerfile` and `.dockerignore`
  - Node.js / npm-based project structure (`.npmignore`, `.npmrc`, `src/` directory)

## Integration & Configuration

- Configure credentials and settings through the provided `.env.example` file (copied to `.env` with real values).
- Configure MCP client integration using `.mcp.json.example` as a template.
- Can be run directly from source or via Docker (Dockerfile provided).

## Pricing

- The project is provided as a public GitHub repository.  
- No paid plans or commercial pricing information are specified in the provided content.