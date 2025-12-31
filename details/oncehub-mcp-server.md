# OnceHub MCP Server

MCP Server for OnceHub, connecting MCP agents to lead capture, qualification, and engagement tools so they can respond to inbound leads quickly.

## Overview
The OnceHub MCP Server is an MCP endpoint that lets MCP-compatible clients interact with OnceHub’s lead capture, qualification, and engagement capabilities. It is provided via a static MCP server URL hosted by Pipedream Connect.

## Features
- **MCP server endpoint for OnceHub**
  - Exposes OnceHub functionality (lead capture, qualification, and engagement) through the MCP protocol.
- **Static server URL**
  - Single, static MCP server URL for all clients:
    - `https://mcp.pipedream.net/v2`
  - Authentication is handled when you add the server to your MCP-compatible application.
- **Client-agnostic integration**
  - Designed to be added to a variety of MCP-compatible chat clients.
- **Lead capture and qualification support**
  - Enables MCP agents to connect to OnceHub tools that capture inbound leads.
  - Supports qualifying leads so they can be processed or routed appropriately.
- **Lead engagement support**
  - Connects MCP agents to engagement and scheduling flows to follow up with inbound leads quickly (minutes instead of days).
- **Central configuration resources**
  - Configuration guidance available via a dedicated Configuration page (linked from the product page).

## Integration & Setup
- **Server URL**: `https://mcp.pipedream.net/v2`
- **Usage pattern**:
  - Add this URL as an MCP server endpoint in your MCP-compatible chat client or application.
  - Authenticate within your client when prompted.
  - Use OnceHub-related tools and actions exposed through the MCP interface to handle leads.

## Pricing
- Not specified in the provided content.

## Additional Information
- **Provider**: Pipedream Connect (integrating OnceHub into MCP)
- **Category**: Business & Commerce – MCP Servers
- **Tags**: lead-management, scheduling, customer-engagement