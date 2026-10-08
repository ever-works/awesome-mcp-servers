## Overview

A Node.js implementation of an MCP server for Webflow, leveraging the Webflow JavaScript SDK to allow AI agents to access Webflow APIs.

## Features

- Remote installation via https://mcp.webflow.com/sse with OAuth authentication
- Local installation using `npx -y webflow-mcp-server@latest` with Webflow API token
- Integration with Cursor and Claude Desktop via mcp.json configuration
- Requires Webflow MCP Bridge App published in workspace for Designer integration
- Available tools listed in ./tools directory

## Installation

### Remote
- Configure in Cursor/Claude: {"mcpServers": {"webflow": {"url": "https://mcp.webflow.com/sse"}}}

### Local
- Set WEBFLOW_TOKEN environment variable
- Run `npx -y webflow-mcp-server@latest`

## Use Cases

- Analyze blog posts and suggest SEO topics
- Add internal links to posts
- Create responsive hero sections

## Limitations

- Static page content updates limited to secondary locales

## Pricing

Free and open-source. Webflow account and API access required.