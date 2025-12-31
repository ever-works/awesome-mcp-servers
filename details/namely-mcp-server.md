# Namely MCP Server

## Overview
Namely MCP Server is an MCP-compatible integration that exposes Namely’s HR, payroll, benefits, and talent management capabilities to MCP-enabled clients (such as chat applications). It is hosted by Pipedream and accessed via a static MCP server URL.

## Features
- **MCP compatibility**
  - Acts as an MCP Server that can be added to MCP-compatible clients (e.g., chat apps).
  - Uses a single static server URL for all clients.

- **Namely platform integration**
  - Provides access to Namely’s core functional areas:
    - Human Resources
    - Payroll
    - Benefits
    - Talent management

- **Authentication per application**
  - Authentication occurs when you add the server to your application, allowing the same MCP endpoint to be reused across different clients.

- **Central configuration**
  - Connect your Namely account and select your client to start using the server.
  - Additional setup details are available via a configuration page (host-specific), guiding how to integrate with specific chat clients.

- **Hosted endpoint**
  - Hosted by Pipedream at a managed URL: `https://mcp.pipedream.net/v2`.

> Note: The page references "available tools" and actions, but they are dynamically loaded and not listed in the provided content, so specific tool-level features cannot be enumerated.

## Technical Details
- **MCP server URL**: `https://mcp.pipedream.net/v2`
- **Deployment model**: Hosted cloud MCP server provided by Pipedream.
- **Client integration**: Add as an MCP Server to supported chat or MCP-enabled applications, then authenticate with Namely.

## Pricing
The provided content does not include any pricing information for the Namely MCP Server or related services.