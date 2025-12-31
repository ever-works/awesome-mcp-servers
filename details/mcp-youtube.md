# mcp-youtube

**Category:** media-processing-mcp-servers  
**Brand:** anaisbetts  
**Source:** https://github.com/anaisbetts/mcp-youtube

## Overview
mcp-youtube is a Model Context Protocol (MCP) server that integrates YouTube subtitles into MCP-compatible clients (such as Claude). It relies on `yt-dlp` to fetch caption data from YouTube videos so that models can summarize or analyze video content via MCP tools.

## Features
- **Model Context Protocol server for YouTube**
  - Exposes YouTube subtitle retrieval as an MCP server, consumable by MCP-compatible clients.
- **Subtitle fetching via `yt-dlp`**
  - Uses `yt-dlp` to download subtitles/captions from YouTube videos.
  - Requires `yt-dlp` to be installed locally (e.g., via Homebrew).
- **Integration with Claude / MCP clients**
  - Designed to connect to Claude via MCP; enables prompts such as “Summarize the YouTube video <url>”.
  - Makes fetched subtitles available as contextual data for downstream LLM tasks (summarization, extraction, etc.).
- **NPM package distribution**
  - Published as `@anaisbetts/mcp-youtube` for installation and integration in MCP setups.
- **TypeScript/JavaScript project structure**
  - Includes TypeScript configuration (`tsconfig.json`) and linting/prettier configs for development.
- **Open source**
  - Source code available on GitHub with a `COPYING` file specifying the license.

## Requirements
- Local installation of `yt-dlp` (for example via Homebrew).
- MCP-compatible client (e.g., Claude with MCP support) to use the server’s capabilities.

## Usage (Conceptual)
- Install and configure `@anaisbetts/mcp-youtube` as an MCP server.
- Ensure `yt-dlp` is installed and accessible in the environment.
- From an MCP client, invoke the YouTube tool (e.g., ask Claude to summarize or analyze a given YouTube URL); the server will fetch subtitles via `yt-dlp` and provide them as context.

## Pricing
- Not specified in the available content (open-source GitHub project; no pricing information provided).
