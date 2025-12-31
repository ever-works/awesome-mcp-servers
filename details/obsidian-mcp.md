# obsidian-mcp

**Category:** document-management-mcp-servers  
**Tags:** notes, knowledge-base, document-management  
**Source:** https://github.com/StevenStavrakis/obsidian-mcp

## Overview
obsidian-mcp is an MCP (Model Context Protocol) server for Obsidian.md that allows AI assistants to interact directly with an Obsidian vault. It provides programmatic tools for reading, creating, editing, and managing notes and tags within the vault.

## Features
- MCP server implementation compatible with Model Context Protocol
- Connects to an existing Obsidian vault via a configured filesystem path
- Read access to Obsidian notes
- Write access to Obsidian notes (create and edit)
- Tools for managing note metadata such as tags
- Designed to be used from AI assistants (e.g., via Claude Desktop configuration)

## Requirements
- An existing Obsidian vault accessible via an absolute filesystem path
- MCP-compatible client (e.g., Claude Desktop) to connect to the server
- Ability to edit the Claude Desktop configuration file:
  - macOS/Linux: `~/Library/Application Support/Claude/claude_desktop_config.json`
  - Windows: `%APPDATA%\Claude\claude_desktop_config.json`

## Installation & Setup
- Manually add obsidian-mcp to the Claude Desktop configuration file.
- Specify the absolute path to your Obsidian vault (e.g., `/path/to/your/vault`).
- Restart Claude Desktop after updating the configuration.
- It is strongly recommended to back up your Obsidian vault (e.g., via Git or other backup methods) before enabling read/write operations, as the MCP is in active development.

## Pricing
- Not specified in the available content (open-source GitHub repository; license present but details not shown in the provided text).