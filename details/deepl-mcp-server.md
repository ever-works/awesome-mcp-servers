# DeepL MCP Server

MCP server for DeepL that allows MCP-compatible applications to access DeepL’s machine translation services.

- **Website / Source**: https://mcp.pipedream.com/app/deepl
- **Category**: AI Integration – MCP Servers
- **Brand**: DeepL
- **Slug**: `deepl-mcp-server`
- **Tags**: `translation`, `nlp`, `ai-integration`

## Features

- Provides an MCP (Model Context Protocol) server interface to DeepL’s translation API.
- Allows MCP-compatible applications (e.g., chat or developer tools) to integrate DeepL translation into their own products and services.
- Exposes a single static MCP server URL usable across all compatible clients:
  - Base URL: `https://mcp.pipedream.net/v2`
- Authentication handled when adding/configuring the server in the client application.
- Can be added to different chat or MCP clients (client-specific setup instructions referenced but not detailed in the source content).
- Hosted and operated via Pipedream Connect infrastructure.

## Usage

- Configure your MCP-compatible client to use the server URL: `https://mcp.pipedream.net/v2`.
- Complete authentication within your chosen client when adding the server.
- Optional: refer to the provider’s full configuration documentation (linked as “Configuration page” in the source) for client-specific setup.

## Pricing

- Not specified in the provided content.