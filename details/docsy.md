# Docsy

Hosted OAuth MCP server for current and version-specific library and framework documentation, with five read-only tools and source links.

## Basic Info

- **Name:** Docsy
- **Category:** Documentation Learning Resources
- **Source URL:** https://github.com/getremcp/docsy-plugin
- **MCP Endpoint:** `https://docsy.remcp.site/mcp/registry`
- **Tags:** `documentation`, `developer-tools`, `oauth`, `remote`

Docsy is a hosted documentation MCP service for coding assistants. Five read-only tools resolve libraries, list indexed versus upstream-only versions, and retrieve focused source-linked excerpts from public framework and SDK documentation.

## Features

- Current and version-specific documentation with canonical source citations.
- OAuth 2.1 authorization for hosted Streamable HTTP: `https://docsy.remcp.site/mcp/registry`.
- No file-system access or mutating tools for the Docsy documentation plugin.
- Public installation and release materials are in the getremcp/docsy-plugin repository.

## Connecting

Add the remote MCP URL `https://docsy.remcp.site/mcp/registry` to an MCP client supporting Streamable HTTP and OAuth. Sign in during the client authorization flow. The unauthenticated server returns HTTP 401 by design.

## Support

Read the [installation instructions](https://github.com/getremcp/docsy-plugin) and [public documentation](https://docsy.remcp.site/docs).
