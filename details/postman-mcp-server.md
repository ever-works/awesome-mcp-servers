## Overview

The Postman MCP Server connects Postman to AI tools, giving AI agents and assistants the ability to access workspaces, manage collections and environments, evaluate APIs, and automate workflows through natural language interactions.

## Key Capabilities

The Postman MCP server enables your AI agents to securely automate your API workflows:
- **API Testing**: Continuously test your API using your Postman collection
- **Code Synchronization**: Effortlessly keep your code in sync with your Postman Collections and specs
- **Collection Management**: Create and tag collections, update collection and request documentation, add comments, or perform actions across multiple collections without leaving your editor

## Server Configurations

Postman supports two tool configurations:

### Minimal (Default)
Only includes essential tools for basic Postman operations. Ideal for users who want to modify a single Postman element, such as collections, workspaces, or environments.

### Full
Includes all available Postman API tools (100+ tools). This configuration is ideal for users who engage in advanced collaboration and Postman's Enterprise features.

## Deployment Options

The remote Postman MCP Server is hosted by Postman over streamable HTTP and provides the easiest method for getting started. For the best developer experience and fastest setup, use OAuth on the remote server (https://mcp.postman.com).

## Authentication

OAuth is fully compliant with the MCP Authorization specification and doesn't require manual API key configuration.

## Additional Features

- Use MCP requests to experiment, test, and evaluate different MCP servers
- Export the MCP server's configuration and use it to set up an MCP host
- Works with Claude Desktop, VS Code, Cursor, and other MCP-compatible tools

## Use Cases

- Automated API testing
- AI-assisted API documentation
- Collection management automation
- API development workflow optimization