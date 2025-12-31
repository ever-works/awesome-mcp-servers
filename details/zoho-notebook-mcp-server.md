# Zoho Notebook MCP Server

An MCP server that connects Zoho Notebook with MCP-compatible clients so agents can create, organize, and sync notes across devices via the MCP protocol.

- **Website / Source**: https://mcp.pipedream.com/app/zoho_notebook
- **Category**: Document Management MCP Servers
- **Provider / Brand**: Pipedream
- **MCP Server URL**: `https://mcp.pipedream.net/v2`

## Features

- **Zoho Notebook integration**: Connects Zoho Notebook as a backend for notes within MCP-compatible applications.
- **Cloud syncing**: Notes are synced to the cloud and remain backed up.
- **Cross-device access**: Notes stay up to date across devices connected to Zoho Notebook.
- **Static MCP endpoint**: Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) that works for all supported MCP clients.
- **Client-agnostic**: Designed to be added to different MCP-enabled chat or agent clients using the same server URL.
- **Authentication at setup**: Authentication occurs when adding the server in the client, rather than requiring a per-client endpoint.

## Usage

- Add the MCP server to a compatible chat or agent client using the static URL: `https://mcp.pipedream.net/v2`.
- Authenticate within the client when prompted to link Zoho Notebook.
- Optionally refer to the provider’s configuration documentation for client-specific setup steps.

## Pricing

- Not specified in the provided content.