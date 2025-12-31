# Height MCP Server

**Category:** Project Management MCP Servers  
**Brand:** Height  
**Source:** https://mcp.pipedream.com/app/height

## Overview
Height MCP Server is an MCP (Model Context Protocol) server that connects Height—a collaborative work and task management platform—to MCP-compatible AI agents. It enables agents to perform project and task operations within Height.

## Features
- **MCP integration endpoint**  
  - Static, shared MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
  - Works as a common endpoint that different MCP-compatible chat or AI clients can use.

- **Height integration**  
  - Connects MCP-based AI agents with Height, allowing them to work with projects and tasks in Height (e.g., task and project operations).

- **Client-agnostic setup**  
  - Same server URL for every supported client.  
  - Authentication is performed when adding the server to the specific application or chat client.

- **Configuration guidance**  
  - Documentation available via a central Configuration page (referenced from the app page) for detailed setup steps per client.

- **Hosted and maintained by Pipedream**  
  - Operated via Pipedream Connect, which provides the infrastructure and hosting for the MCP server.

## Authentication
- Authentication to Height occurs when you add the MCP server to your application or chat client.  
- The MCP URL stays the same; credentials/authorization are handled per-client.

## Getting Started
1. Use the MCP server URL: `https://mcp.pipedream.net/v2`.
2. Add this server to your MCP-compatible chat client or AI application.
3. Follow the client-specific configuration instructions from the Configuration page.
4. Authenticate your Height account during setup so the agent can access and manage Height tasks and projects.

## Pricing
- No pricing information is provided in the available content.