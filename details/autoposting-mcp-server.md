## Overview

Autoposting is a hosted MCP server that gives an AI client full control of a social media workflow: draft and rewrite posts, generate ideas with AI agents, build carousels, clip and render video, search a knowledge base, manage brands and webhooks, and schedule or publish to X, LinkedIn, Instagram, Threads and YouTube. It speaks Streamable HTTP and authenticates with OAuth 2.1 Dynamic Client Registration, so there is no client ID or secret to configure and nothing to install locally.

## Features

- 69 tools across posts, ideas and agents, brands, knowledge base, carousels, video clips, webhooks, and organizations
- Schedule and publish to X, LinkedIn, Instagram, Threads and YouTube
- AI idea generation and post rewriting
- Carousel generation and drafting
- Video clip import, rendering, and management
- Knowledge base ingestion and search
- Brand and webhook management
- Tools filtered per connection by OAuth scope
- MCP annotations on every tool so a client can tell reads from writes and confirm before a destructive call

## Setup

Claude Code:
```
claude mcp add --transport http autoposting https://app.autoposting.ai/mcp
```

Claude Desktop / Cursor / generic client:
```json
{
  "mcpServers": {
    "autoposting": {
      "type": "http",
      "url": "https://app.autoposting.ai/mcp"
    }
  }
}
```

OAuth 2.1 Dynamic Client Registration handles authentication, so no client ID or secret needs to be configured.

## Pricing

Requires an Autoposting account. See https://autoposting.ai for plan details.

## Best For

Teams and creators who want an AI client to run a multi-platform social media workflow end to end without installing or hosting anything.
