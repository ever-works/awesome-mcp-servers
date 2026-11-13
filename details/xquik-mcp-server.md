## Overview

Xquik MCP Server exposes a credential-scoped X data API through 2 MCP tools. It uses Streamable HTTP at `https://xquik.com/mcp`.

## Capabilities

- `explore` searches the operation catalog without making network calls
- `xquik` executes authenticated API requests
- Full account API keys and OAuth tokens expose 118 operations
- Active guest keys expose 33 eligible read operations
- Public data reads do not require a connected X account
- Writes and private account reads require a connected X account

## Integration

- Endpoint: `https://xquik.com/mcp`
- Transport: Streamable HTTP
- Authentication: OAuth 2.1 or an Xquik API key
- Discovery: `https://xquik.com/.well-known/mcp.json`
- Documentation: `https://docs.xquik.com/mcp/overview`

OAuth 2.1 is recommended. Clients without OAuth can send an API key through the `x-api-key` header when they support secure header storage.

## Use Cases

- Search tweets and inspect accounts, trends, lists, and communities
- Analyze timelines and follower relationships
- Download tweet media and read long-form X articles
- Run monitoring and authorized account workflows

## Category

Social

## Tags

social-media, x-data, remote, oauth2, streamable-http

## Source

[https://github.com/Xquik-dev/x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper)

## License

MIT License
