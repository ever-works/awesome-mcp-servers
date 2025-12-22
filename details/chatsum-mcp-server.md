# ChatSum MCP Server

## Description
ChatSum MCP Server is a Model Context Protocol (MCP) server that lets LLMs query and summarize chat messages stored in a chat database, enabling conversational log analysis and condensation.

## Features
- Summarize chat messages stored in a local chat database
- Allow LLMs to query historical conversations for analysis and condensation
- Integrates with a separate `chatbot` component that captures and saves chat messages
- Exposes an MCP tool:
  - `query_chat_messages` – query stored chat messages from the database
- Designed to work with MCP-compatible clients (e.g., Claude Desktop)
- Supports environment-based configuration for the chat database location
- Development setup with build and auto-rebuild workflows
- Debugging support via MCP Inspector in the browser

## Installation & Setup
- Prepare chat database:
  - Go to the `chatbot` directory and follow its `README` to set up the chat database.
  - Start the chatbot so that it saves your chat messages to the database.
- Server configuration:
  - In the MCP server root directory, create a `.env` file and set your chat database path.
- Build the server:
  - Follow the build steps indicated in the repository (supports normal build and development with auto-rebuild).

## Usage
- Use with Claude Desktop by adding the MCP server configuration to:
  - macOS: `~/Library/Application Support/Claude/claude_desktop_config.json`
  - Windows: `%APPDATA%/Claude/claude_desktop_config.json`
- Once configured, the MCP tool `query_chat_messages` can be used by the client to access and summarize stored chat logs.

## Configuration
- `.env` (in project root):
  - Contains the path to your chat database used by the server.

## Debugging
- MCP servers communicate over stdio, so debugging is aided via the MCP Inspector:
  - Run the provided MCP Inspector script from the project.
  - Open the URL printed by the Inspector to access browser-based debugging tools for the server.

## Pricing
- Open-source GitHub project; no pricing information or paid plans are specified.