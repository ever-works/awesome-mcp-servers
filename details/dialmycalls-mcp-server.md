# DialMyCalls MCP Server

## Overview
DialMyCalls MCP Server is an MCP-compatible integration that connects the DialMyCalls voice and SMS broadcasting service to MCP-enabled applications. It allows users to create a message and send it to all of their contacts instantly through automated workflows.

## Features
- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Can be added to any supported MCP client or chat application.

- **Voice and SMS broadcasting**  
  - Supports creating a single message and broadcasting it to multiple contacts.  
  - Works with both voice calls and SMS messages.

- **Account integration**  
  - Connects to a DialMyCalls account to access broadcasting capabilities.  
  - Uses authentication when the MCP server is added to an application.

- **Client-agnostic configuration**  
  - Same MCP server URL works across different clients.  
  - Configuration instructions available per chat client via the configuration page.

- **Tool-based actions (via MCP)**  
  - Exposes DialMyCalls actions as MCP “tools” for use inside compatible applications (e.g., sending broadcasts, managing communication workflows).  
  - Tools are discoverable from within the MCP client once the server is configured.

## Configuration
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to any supported MCP/chat client and authenticate with your DialMyCalls account.
- Additional configuration details are available on the Pipedream configuration page.

## Pricing
- Not specified in the provided content.