# TalentLMS MCP Server

## Overview
The **TalentLMS MCP Server** is an MCP-compatible integration endpoint that allows AI agents and chat-based clients to connect to TalentLMS. It is designed to work with the static MCP URL:

```text
https://mcp.pipedream.net/v2
```

Once added to a compatible client, you authenticate within your application to enable interaction with TalentLMS resources.

## Features
- **MCP-compatible server**: Exposes a TalentLMS integration over the Model Context Protocol (MCP) for use with AI/chat clients.
- **Static server URL**: Uses a single, static endpoint (`https://mcp.pipedream.net/v2`) that can be reused by any client.
- **In-app authentication**: Authentication occurs when the server is added to the client/application, instead of per-URL customization.
- **Client-agnostic setup**: Can be added to multiple MCP-capable chat clients; setup instructions are provided per client via the configuration docs.
- **Pipedream Connect integration**: Provided and hosted via Pipedream Connect’s infrastructure.

> Note: The underlying description indicates it is intended to integrate with TalentLMS training workflows, content, and user management, but the public page above only exposes the server URL and high-level positioning, without listing specific API methods or tools.

## Configuration
- **MCP Server URL**: `https://mcp.pipedream.net/v2`
- **Setup**: Add the URL as an MCP server in your chat/AI client, then follow that client’s instructions to authenticate.
- **Additional configuration details**: Available on the provider’s configuration page (not fully detailed in the provided content).

## Pricing
The provided content does not include any pricing information for the TalentLMS MCP Server.