# TypeflowAI MCP Server

## Overview
The **TypeflowAI MCP Server** is an MCP (Model Context Protocol) service that exposes TypeflowAI—a no-code platform for building AI tools and workflows—so it can be integrated into compatible chat clients and AI applications.

- **Category:** AI Integration – MCP Servers  
- **Brand:** typeflowai  
- **Use case:** Connect TypeflowAI’s no-code AI workflows into MCP-compatible clients and tools.

## Features
- **MCP-compliant server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL works across supported clients; authentication occurs when adding the server to the application.

- **No-code AI workflow integration**  
  - Leverages TypeflowAI’s no-code environment for building AI tools and workflows.  
  - Allows those tools/workflows to be exposed as MCP tools inside compatible clients.

- **Multi-client support**  
  - Can be added to different chat or MCP-compatible clients.  
  - Client-specific setup instructions are available via the “Add the server to your app” flow and configuration page.

- **Configurable via TypeflowAI account**  
  - Connect a TypeflowAI account through Pipedream to configure access.  
  - Once connected, available tools/actions defined in TypeflowAI are exposed via the MCP server (tools list is dynamically loaded).

- **Hosted by Pipedream**  
  - MCP server is provided as a managed endpoint by Pipedream, reducing the need for custom hosting.

## Integration & Setup
- Copy the static MCP server URL: `https://mcp.pipedream.net/v2`.  
- Add the server URL to your MCP-compatible chat client or application.  
- Authenticate when prompted to link your TypeflowAI configuration.  
- Optionally consult the full configuration documentation on the Pipedream configuration page.

## Pricing
Pricing details are not specified in the provided content.