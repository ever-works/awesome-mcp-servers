# Gmail MCP Server

A Model Context Protocol (MCP) server that integrates Gmail into Claude Desktop, providing automated authentication and natural-language control over Gmail.

- **Category:** MCP Server Directories / Lists  
- **Source:** [GitHub – GongRzhe/Gmail-MCP-Server](https://github.com/GongRzhe/Gmail-MCP-Server)  
- **License:** MIT  
- **Brand:** Google (Gmail integration)

## Overview
Gmail MCP Server exposes Gmail functionality to AI assistants via the Model Context Protocol, allowing Claude Desktop to interact with a user’s Gmail account. It supports automatic authentication flows and enables common email operations to be driven by natural-language instructions.

## Features
- **Model Context Protocol server** specifically designed for Gmail.  
- **Claude Desktop integration** to use Gmail directly from the Claude desktop app.  
- **Automated authentication support** for connecting a Gmail account.  
- **Email operations via natural language**, enabling AI assistants to manage Gmail (e.g., interacting with messages and mailbox state) through conversational commands.  
- **Open-source implementation** with Dockerfile and docker-compose configuration for containerized deployment.  
- **Configuration via `mcp-config.json`** for integrating with MCP-compatible clients.  
- **Filter and query examples** (`filter-examples.md`) to guide constructing Gmail queries.  
- **Documentation for LLM installation/usage** (`llms-install.md`) to help wire the server into LLM-based tools.

## Pricing
- **Free & Open Source** – Available at no cost under the MIT License.