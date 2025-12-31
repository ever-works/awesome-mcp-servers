# GraphQL Schema MCP Server

A Model Context Protocol (MCP) server that exposes GraphQL schema information to Large Language Models (LLMs), enabling them to explore and understand GraphQL schemas efficiently.

- **Category:** Development Tools – MCP Servers  
- **Tags:** graphql, schema-inspection, developer-tools  
- **Source:** https://github.com/hannesj/mcp-graphql-schema

## Features

- Exposes GraphQL schema information to LLMs via MCP.
- Provides specialized tools for exploring and understanding GraphQL schemas.
- Designed to work with LLMs such as Claude (Claude Desktop and Claude Code).
- Can be run from the command line with a specified GraphQL schema file.
- Distributable/usable via Smithery for easier installation and management.
- Integrates with Claude Desktop through `claude_desktop_config.json` configuration.
- Integrates with Claude Code CLI by adding the server to its configuration.

## Usage

### Command Line
- Run the MCP server with a specific GraphQL schema file (details in the repository’s README).

### Claude Desktop Integration
- Edit `claude_desktop_config.json` to register the GraphQL Schema MCP server.
- Typical locations:
  - macOS: `~/Library/Application Support/Claude/claude_desktop_config.json`
  - Windows: `$env:AppData\Claude\claude_desktop_config.json`

### Claude Code Integration
- Add the GraphQL Schema MCP server to the Claude Code CLI configuration (see README for exact configuration snippet).

### Installation via Smithery
- Install and manage the MCP server for Claude Desktop via Smithery:  
  https://smithery.ai/server/@hannesj/mcp-graphql-schema

## Pricing

- Not specified in the provided content. (Project appears to be an open-source GitHub repository; consult the repository for any licensing or pricing details.)

## License

- A `LICENSE` file is present in the repository; see the GitHub repository for exact license terms.