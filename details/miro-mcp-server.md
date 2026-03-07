## Overview

Miro offers a hosted MCP server that gives MCP-compatible clients secure access to Miro boards within organizations. The MCP Miro Server integrates with the Miro platform, enabling AI assistants like Claude to access, view, and manage Miro boards through a standardized interface.

## Key Features

- **Board Management**: Create and manipulate boards programmatically
- **Sticky Note Creation**: Create sticky notes with specified content and position
- **Shape Manipulation**: Create or modify shapes to organize content visually
- **Content Reading**: Read board contents, frames, and current contents for display or processing
- **Bulk Operations**: Perform batch operations on board elements
- **Enterprise Features**: Handle enterprise-level collaboration needs

## Community Implementations

### evalstate/mcp-miro
A Model Context Protocol server to connect to the MIRO Whiteboard Application that allows board manipulation, sticky creation, bulk operations and more.

### @k-jarzyna/mcp-miro
Integrates with Miro's collaborative whiteboard platform, providing over 80 tools for managing boards, creating and manipulating various item types, and handling enterprise features.

## Installation

For Claude Desktop, you can install automatically via Smithery:
```bash
npx -y @smithery/cli install @llmindset/mcp-miro --client claude
```

For the official Miro MCP Server, configure with URL `https://mcp.miro.com/` in your MCP client settings.

## Authentication

Uses OAuth 2.1 with dynamic client registration for secure access.

## Use Cases

- AI-powered brainstorming session management
- Automated workshop board setup
- Content organization and visualization
- Team collaboration automation