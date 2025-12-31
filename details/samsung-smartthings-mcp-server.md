# Samsung SmartThings MCP Server

Samsung SmartThings MCP Server is an MCP server that connects the Samsung SmartThings smart home platform with AI tools, enabling control and monitoring of compatible home devices via the Model Context Protocol.

- **Website / Source**: https://mcp.pipedream.com/app/smartthings
- **Category**: Messaging MCP Servers
- **Brand**: Samsung SmartThings
- **Tags**: smart-home, iot, home-assistant

## Features

- **MCP-compatible server**: Exposes SmartThings functionality through the Model Context Protocol, so AI clients and tools that support MCP can interact with SmartThings.
- **Smart home integration**: Connects to the Samsung SmartThings platform to enable control and monitoring of supported smart home and IoT devices.
- **Static server URL**: Uses a single static MCP endpoint usable across clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic setup**: Designed to be added to various MCP-compatible chat or AI clients using the same server URL.
- **Authentication at client setup**: Authentication is performed when adding the server to an application/client (details handled during client configuration).
- **Hosted by Pipedream**: Operates on Pipedream’s infrastructure via Pipedream Connect.

## Configuration

- Add the following MCP server URL to your MCP-compatible client:
  - `https://mcp.pipedream.net/v2`
- Follow your client’s instructions for adding a new MCP server and authenticate during setup.
- Additional configuration details are available on the Pipedream MCP Configuration page (linked from the source).

## Pricing

- No pricing information is provided in the available content.