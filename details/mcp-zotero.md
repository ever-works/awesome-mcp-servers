# mcp-zotero

**Category:** Documentation & Learning Resources  
**Tags:** reference-management, Zotero, research

## Overview
mcp-zotero is an open-source Model Context Protocol (MCP) server that connects Claude (e.g., Claude Desktop) to your Zotero Cloud library. It enables LLMs to access, search, and work with your Zotero collections and references via the Zotero API.

- **Developer / Brand:** kaliaboi  
- **Source Code:** https://github.com/kaliaboi/mcp-zotero  
- **License:** MIT

## Features
- **MCP server for Zotero**  
  - Implements a Model Context Protocol server specifically for Zotero integration.
  - Designed to let Claude interact with your Zotero library through the MCP protocol.

- **Zotero Cloud integration**  
  - Connects to Zotero’s cloud-based API using your Zotero API key and user ID.  
  - Works with your existing online Zotero account and library.

- **Library and collections access**  
  - Allows Claude to work with your Zotero collections and stored sources.  
  - Supports interaction with items in your Zotero library (references, notes, and related metadata) subject to your API key permissions.

- **Credential-based configuration**  
  - Uses a personal Zotero API key generated at `https://www.zotero.org/settings/keys`.  
  - Requires your Zotero `userID`, retrieved via the Zotero API using your key.  
  - Environment variables are used for configuration (e.g., API key and user ID).

- **CLI / API verification steps**  
  - Provides example curl/HTTP commands to verify that your Zotero credentials (API key and user ID) are valid before using the server.

- **Containerization and tooling**  
  - Includes a `Dockerfile` for container-based deployment.  
  - TypeScript-based codebase with `tsconfig.json` for compilation settings.  
  - `package.json` for dependency management and scripts.  
  - `.gitignore` for common development artifacts.

- **Smithery configuration**  
  - Includes `smithery.yaml`, indicating integration or compatibility with MCP tooling/registry (e.g., for easier installation or discovery of the MCP server).

## Setup (Summary)
- Create a Zotero API key in your Zotero account settings.  
- Use the API key to query Zotero and obtain your `userID`.  
- Export your API key and user ID as environment variables.  
- Run or integrate the MCP server so Claude can access your Zotero library.

## Pricing
- **Open-source / Free**  
  - Distributed under the MIT license.  
  - No pricing plans are specified; usage is subject to Zotero’s own API and account terms.