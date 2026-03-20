## Overview

Vercel launched the official Vercel MCP server in Public Beta, which is a secure, OAuth-compliant interface that lets AI clients interact with your Vercel projects. Supported tools like Cursor and Claude can securely access logs, docs, and project metadata directly from within your development environment or AI assistant.

## Vercel AI SDK MCP Integration

AI SDK 6 extends MCP support to cover OAuth authentication, resources, prompts, and elicitation, with the functionality now stable and available in the @ai-sdk/mcp package.

### Key Features

**MCP Client Support**: The Vercel AI SDK includes MCP client capabilities through the experimental_createMCPClient() function. Once connected, tools from any MCP server become available to your AI model through the same interface as native AI SDK tools.

**Transport Mechanisms**: The protocol formally specifies stdio and HTTP (optionally with SSE) as its standard transport mechanisms:
- **stdio**: Works for local MCP servers
- **SSE (Server-Sent Events)**: Enables remote MCP servers accessible over HTTP

**Streaming Support**: Vercel MCP supports the MCP Authorization and Streamable HTTP specifications, ensuring protocol best practices.

## Available Capabilities

### Project Access

- Secure access to Vercel project metadata
- Deployment information
- Build logs and runtime logs
- Environment variables (read-only)
- Project configuration

### Documentation Integration

- AI-powered search and querying of Vercel AI SDK documentation
- Contextual responses based on official documentation
- Developer guidance and best practices

## Security Features

- OAuth authentication for secure access
- Token-based authorization
- Read-only access to sensitive data
- Compliance with security best practices

## Compatible Clients

- Cursor IDE
- Claude Desktop and Claude Code
- GitHub Copilot
- VS Code extensions
- Any MCP-compatible AI assistant

## AI SDK 6 Features

The latest AI SDK includes:
- Stable MCP support in @ai-sdk/mcp package
- OAuth authentication support
- Resources and prompts integration
- Elicitation capabilities
- Streamable HTTP compliance

## Use Cases

- Debugging deployment issues from AI chat
- Querying project configurations
- Accessing build and runtime logs
- Documentation lookup during development
- Project metadata exploration
- Environment variable management

## Technical Specifications

- **Package**: @ai-sdk/mcp
- **Protocol**: Model Context Protocol (MCP)
- **Authentication**: OAuth 2.0
- **Transport**: HTTP with SSE, stdio
- **Status**: Public Beta

## Integration Setup

1. Visit Vercel MCP server endpoint
2. Authenticate with OAuth
3. Configure in your AI assistant
4. Access Vercel projects and documentation

## Pricing

Included with Vercel accounts. No additional cost for MCP server access.