# wenyan-mcp

**Brand:** caol64  
**Category:** content-management-mcp-servers  
**Repository:** https://github.com/caol64/wenyan-mcp  
**License:** Apache-2.0

## Description
wenyan-mcp is an MCP (Model Context Protocol) server that enables AI agents to automatically format Markdown articles and publish them to WeChat Official Accounts (公众号/GZH). It is tailored for Wenyan-style content workflows, handling the conversion from raw Markdown to WeChat-ready, properly typeset posts.

## Features
- **MCP server for AI tools**
  - Exposes functionality via the Model Context Protocol so AI agents can call it programmatically.
- **Automatic Markdown formatting**
  - Takes Markdown input and applies layout/typographic rules suitable for WeChat Official Accounts.
- **WeChat Official Account publishing**
  - Supports end-to-end flow from formatted article to publishing on WeChat Official Accounts (GZH).
- **Wenyan-style workflow support**
  - Designed around Wenyan-style content creation and publishing pipelines.
- **Containerization support**
  - Includes a Dockerfile for containerized deployment.
- **Configurable project structure**
  - Organized `src`, `data`, and `test` directories, allowing customization and extension of behavior.

## Technical Details
- **Language/Runtime:** Node.js (inferred from `package.json` and `pnpm-lock.yaml`).
- **Dependency management:** pnpm lockfile included.
- **Version control:** Public GitHub repository with branches and tags.

## Pricing
- Not specified in the available content. The project is open source under the Apache-2.0 license; no paid plans are described.