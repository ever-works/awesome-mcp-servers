## Overview

MCP is a protocol that enables AI tools and applications to connect with Intercom's data and services in a secure, standardized way. The new Intercom MCP Server, powered by Cloudflare's infrastructure, lets external AI systems connect directly to your Intercom data – securely and in real time.

## Key Features

- **Structured Data Access**: Find and retrieve Intercom data (conversations, contacts, etc.)
- **Tool Access**: Access specific tools and functionality provided by Intercom
- **Context Maintenance**: Maintain context about your Intercom workspace when working with AI assistants
- **Fin Integration**: Connect Fin with a wide range of tools through standardized setup

## Authentication Options

Supports two authentication approaches:
1. **OAuth Flow (Recommended)**: Automatic browser-based authentication
2. **Bearer Token**: Token-based authentication

## Configuration

Basic OAuth setup configuration:
```json
{
  "mcpServers": {
    "intercom": {
      "command": "npx",
      "args": ["mcp-remote", "https://mcp.intercom.com/mcp"]
    }
  }
}
```

## Use Cases

- **Fin AI Assistant**: Connect to MCP servers for quick integration with external tools
- **Data Access**: Fin can access data and perform actions in external systems
- **Customer Support Automation**: Automate responses and data retrieval
- **Conversation Management**: Manage customer conversations through AI

## Limitations

Currently, the Intercom MCP server is only supported in US hosted workspaces.

## Integration

Multiple implementations available including official Intercom MCP servers, third-party servers on GitHub (fabian1710/mcp-intercom), and integrations through platforms like Composio and Zapier.