## Overview

As launch partners with Anthropic, Sourcegraph has ensured that Cody can seamlessly integrate with MCP, bringing additional context directly into your editor. The Sourcegraph MCP server provides AI-enhanced code search capabilities using Sourcegraph's universal code search platform.

## Key Features

- **Universal Code Search**: Search across multiple repositories and codebases
- **MCP Tool Integration**: Configure one or more local MCP servers through extension settings
- **Automatic Tool Invocation**: Cody determines which tools to invoke and automatically integrates output into response context
- **OpenCtx Integration**: Connect Cody and your editor to MCP servers via OpenCtx
- **Frictionless OAuth**: Generally available with OAuth setup enabled by default

## Integration Method

Users can configure MCP servers through their extension settings. When a user submits a query, Cody:
1. Determines which tools to invoke
2. Passes appropriate parameters
3. Automatically integrates the output into the response context

The integration uses the OpenCtx provider for Model Context Protocol.

## GitHub Repository

Available at github.com/najva-ai/sourcegraph-mcp for the MCP server implementation.

## Use Cases

- **Increased Agent Accuracy**: Leverage powerful code search and navigation tools
- **Build Internal Tools**: Connect to internal documentation and services
- **External Service Access**: Connect to external services with standardized context delivery
- **Multi-repository Search**: Search across entire codebase ecosystems
- **Code Navigation**: Navigate complex codebases with AI assistance

## Availability

Sourcegraph MCP server is now generally available with frictionless OAuth setup.

## Integration

Works with Cody VS Code plugin and other MCP-compatible development environments.