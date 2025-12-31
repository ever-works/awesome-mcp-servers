# mcp-googletasks

## Overview
mcp-googletasks is a Model Context Protocol (MCP) server that connects Large Language Models (LLMs), such as Claude, to the Google Tasks API. It enables programmatic creation and management of Google task lists and tasks directly from an LLM environment.

- **Category:** Project Management MCP Servers  
- **Repository:** https://github.com/arpitbatra123/mcp-googletasks  
- **License:** MIT

## Features
- **MCP server for Google Tasks**  
  - Implements a Model Context Protocol server that exposes Google Tasks functionality to LLMs.
- **Task list management**  
  - Provides operations over Google Task lists (e.g., access and management of lists).  
- **Task management**  
  - Allows creating and managing individual tasks via the Google Tasks API.  
- **LLM integration (Claude-focused)**  
  - Designed to be used from Claude, letting the model call tools to work with Google Tasks programmatically.
- **Google Tasks API bridge**  
  - Acts as an interface layer between the LLM and the official Google Tasks API.
- **Configuration via environment file**  
  - Uses an `.env` configuration file for setting required environment variables and credentials.
- **TypeScript/Node.js implementation**  
  - Source structured under `src/` with TypeScript configuration via `tsconfig.json`.  
  - Managed via `package.json` and `package-lock.json`.
- **Assets and screenshot**  
  - Includes assets and a `screenshot.png` illustrating the integration or usage.

## Pricing
- Not specified (open-source under the MIT license in the public GitHub repository).
