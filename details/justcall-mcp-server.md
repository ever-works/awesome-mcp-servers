# JustCall MCP Server

**Category:** Messaging MCP Servers  
**Brand:** JustCall (SaaS Labs)

## Overview
JustCall MCP Server is an MCP integration that exposes JustCall’s cloud-based phone and SMS system to MCP-compatible applications. It allows applications and chat clients to interact with JustCall for making and receiving calls and texts via a standardized MCP endpoint.

## Features
- **MCP-based integration for JustCall**: Provides an MCP Server layer on top of JustCall’s cloud telephony and SMS platform.
- **Cloud phone capabilities**: Access JustCall’s cloud-based phone system to make and receive business phone calls.
- **SMS messaging**: Send and receive SMS messages through JustCall within MCP-compatible tools.
- **Remote access**: Enables phone and text operations from anywhere via the cloud-based JustCall service.
- **Static MCP endpoint**: Uses a single, static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
- **Per-client authentication**: Authentication is performed when adding the server to each client/application, allowing secure, individualized access.
- **Chat client integration**: Can be added to compatible chat clients to initiate and manage calls and texts through conversational interfaces.

## Configuration
- **MCP Server URL**: `https://mcp.pipedream.net/v2` (same for all clients; credentials handled during setup).  
- **Client setup**: Add the MCP server URL in your MCP-compatible app or chat client, then authenticate with your JustCall / Pipedream credentials as instructed by the client.
- **Additional docs**: Full configuration instructions are available on the Pipedream Connect configuration page.

## Pricing
No explicit pricing details or plans are provided in the available content for the JustCall MCP Server integration. Pricing may depend on JustCall and/or Pipedream Connect subscriptions.