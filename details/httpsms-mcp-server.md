# httpSMS MCP Server

## Overview
The httpSMS MCP Server is an MCP-compatible server that lets you use an Android phone as an SMS gateway, enabling programmatic sending and receiving of SMS via MCP-enabled agents and applications.

- **Name:** httpSMS MCP Server
- **Category:** Messaging MCP Servers
- **Use case:** Turn an Android device into an SMS gateway accessible from MCP-compatible clients.
- **Source URL:** https://mcp.pipedream.com/app/httpsms

## Features
- **Android phone as SMS gateway**
  - Uses an Android device to send and receive SMS messages.
  - Exposes SMS functionality to MCP-compatible agents and applications.

- **MCP-compatible server**
  - Provides a server endpoint that conforms to the Model Context Protocol (MCP).
  - Can be added to MCP-capable chat or automation clients as an external tool.

- **Static MCP server URL**
  - Single, static base URL for the MCP server: `https://mcp.pipedream.net/v2`.
  - Same URL works across all supported clients.

- **Authentication at client configuration**
  - Authentication is performed when adding the server to your application.
  - Keeps the MCP server URL static while securing access per client/account.

- **Configurable via httpSMS account**
  - Requires configuration of an httpSMS account and Android device to operate as the SMS gateway.
  - Central place to connect your account and manage the client configuration.

- **Client-agnostic integration**
  - Can be integrated with multiple MCP-compatible chat clients or tools.
  - Documentation / configuration instructions are organized by client type.

## Integration & Setup
- Configure an httpSMS account and Android device.
- Use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the MCP server to your chosen MCP-compatible client and complete authentication.

## Pricing
Pricing information is not provided in the available content.