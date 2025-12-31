# Time MCP Server

**Category:** AI Integration – MCP Servers  
**Source:** https://github.com/TheoBrigitte/mcp-time  
**License:** MIT

## Overview
Time MCP Server is a Model Context Protocol (MCP) server that provides utilities for working with time and dates. It supports natural language input, multiple time and date formats, and timezone conversion, exposing these capabilities as tools that can be used by MCP-compatible AI clients.

## Features
- **MCP-compatible server**  
  - Implements the Model Context Protocol to expose time-related tools to AI models and MCP clients.

- **Time and date utilities**  
  - Operations focused on working with dates and times (parsing, formatting, conversion and related utilities; exact tool list is defined in the repository code).

- **Natural language handling**  
  - Accepts natural language-style time and date expressions (e.g., human-readable phrases) for processing.

- **Multiple formats support**  
  - Works with different time and date formats for both input and output.

- **Timezone conversion**  
  - Converts times between different timezones.

- **Multi-environment setup**  
  - Project structure includes support for Go builds, Docker, and npm-based usage (as indicated by `cmd/`, `docker/`, `npm/`, and `pkg/` directories).

- **Changelog and workflows**  
  - Version changes tracked via `CHANGELOG.md`.
  - GitHub workflows present for CI/CD automation.

## Technical Details
- **Language:** Go  
- **Distribution/usage options:**
  - Go module (via `go.mod` and `go.sum`).
  - Docker configuration available under `docker/`.
  - npm-related integration under `npm/`.

## Pricing
- Not applicable; the project is open source under the MIT license, with no pricing plans listed.