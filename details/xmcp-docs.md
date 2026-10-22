# xmcp Docs

**Category:** Documentation & Learning Resources  
**Source:** [Official setup guide](https://xmcp.dev/docs/guides/xmcp-mcp-server)

xmcp Docs is the official documentation MCP server for the xmcp TypeScript framework. It lets AI coding agents search the documentation and retrieve pages through one read-only `search` tool.

## Features

- Search documentation using a query, or retrieve a page using its ID.
- Remote Streamable HTTP endpoint: `https://xmcp.dev/mcp`.
- No authentication required.
- Source code is available under the MIT license in the [xmcp monorepo's website application](https://github.com/basementstudio/xmcp/tree/main/apps/website).

## Connecting

Use `https://xmcp.dev/mcp` in a client that supports remote Streamable HTTP. For a stdio-only client, the setup guide uses the `mcp-remote` bridge:

```json
{
  "mcpServers": {
    "xmcp-docs": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://xmcp.dev/mcp"]
    }
  }
}
```

This entry describes the hosted documentation server. The `xmcp` npm package is the framework used to build MCP servers, not an executable package for this hosted Docs server.

## Pricing

Free to use.
