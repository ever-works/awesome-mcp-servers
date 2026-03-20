## Overview

Cloudflare runs a catalog of managed remote MCP servers which you can connect to using OAuth on clients like Claude, Windsurf, or any SDK that supports MCP. MCP clients can read configurations, process information, make suggestions, and even make changes across Cloudflare services.

## Features

### Edge Network Deployment

- **Fastest Cold Starts**: Near-zero millisecond cold starts
- **Global Edge Deployment**: Deploy across Cloudflare's worldwide network
- **Generous Free Tier**: 100K requests per day free indefinitely
- **Official Support**: Cloudflare provides an official MCP server template

### Hosting Features

- **Remote Server Connectivity**: Build remote servers that connect to APIs through Cloudflare's global edge network
- **OAuth Integration**: Secure authentication with OAuth sign-in
- **Token-Efficient Streaming**: Optimized for AI usage patterns
- **Simplified Deployment**: Cloudflare handles the hard parts of building remote MCP servers

### Security Features (2026)

Cloudflare MCP Server Portals are now available in Open Beta, enabling:

- Centralization of MCP connections
- Security controls for all MCP traffic
- Observation of every MCP connection in organizations
- Enterprise-grade access management

## Getting Started

Use the Wrangler CLI to create a new MCP Server:

```bash
npm create cloudflare@latest -- remote-mcp-server-authless --template=cloudflare/ai/demos/remote-mcp-authless
```

## Available MCP Servers

Cloudflare offers thirteen MCP servers covering various use cases including API management, security, analytics, and infrastructure operations.

## Use Cases

- API configuration and management
- Security policy automation
- Performance monitoring and analytics
- Infrastructure as code operations
- Edge computing applications
- Global service deployment

## Technical Specifications

- Support for HTTP and stdio transports
- Integration with Cloudflare Workers
- Access to Cloudflare API endpoints
- Built on Cloudflare's global network

## Pricing

Free tier: 100K requests per day
Paid tiers available for higher usage