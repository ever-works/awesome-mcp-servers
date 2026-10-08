## Overview

BulkPublish provides a REST API and MCP server that lets AI agents plan, adapt, schedule, publish, and analyze social media content across connected platforms.

## Features

- Platform-specific content variants and scheduling
- Media uploads and channel management
- Post status, analytics, and retry workflows
- Local stdio MCP installation through the published npm package
- Hosted MCP transport for compatible clients

## Setup

Install the MCP server with:

```bash
npx -y @bulkpublish/mcp-server
```

Set `BULKPUBLISH_API_KEY` and follow the [MCP documentation](https://app.bulkpublish.com/docs) for client configuration. The [source repository](https://github.com/azeemkafridi/bulkpublish-api) includes the API, MCP server, examples, and reusable [social-media-content-skills](https://github.com/azeemkafridi/bulkpublish-api/tree/main/skills/social-media-content-skills).

## Safety

The API and MCP server require credentials and can write to connected social accounts. Review and approve scheduling or publishing actions before execution.
