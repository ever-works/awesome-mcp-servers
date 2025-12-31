# Phrase MCP Server

**Description**

Phrase MCP Server is an MCP (Model Context Protocol) server that exposes the Phrase localization platform APIs to MCP-compatible clients. It allows agents and applications to manage translations and localization workflows programmatically via a unified MCP endpoint.

- **Website / Source**: https://mcp.pipedream.com/app/phrase
- **Category**: Content Management MCP Servers
- **Tags**: localization, i18n, translations
- **Provider / Brand**: Phrase (hosted via Pipedream Connect)
- **MCP Server URL**: `https://mcp.pipedream.net/v2`

## Features

- **MCP-compatible localization API access**  
  - Exposes Phrase localization platform APIs through an MCP server endpoint.  
  - Designed to be used by MCP-aware agents and chat clients.

- **Static MCP server URL**  
  - Single static server URL (`https://mcp.pipedream.net/v2`) works for all supported clients.  
  - Authentication is handled when adding/configuring the server in the client.

- **Programmatic translation management**  
  - Enables programmatic interaction with Phrase for managing translations and localization workflows (via MCP).  
  - Suitable for integrating localization operations into automated or agent-driven workflows.

- **Client-agnostic integration**  
  - Works with multiple MCP-compatible chat clients; the same URL is used regardless of client.  
  - Configuration instructions are available per client and via a central configuration page.

- **Pipedream Connect integration**  
  - Hosted and powered by Pipedream Connect, enabling easy connection and configuration within the Pipedream ecosystem.

## Integration & Configuration

- Use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-compatible application or chat client.
- Authenticate during the “add server” step as required by your client.
- Additional configuration instructions are available on the Pipedream configuration page for MCP servers.

## Pricing

The provided content does not specify any pricing or plans for Phrase MCP Server.