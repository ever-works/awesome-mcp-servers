# VisualPing MCP Server

Website change detection, monitoring, and alerting via a Model Context Protocol (MCP) server.

## Overview
The VisualPing MCP Server is an integration that exposes VisualPing’s website change detection and monitoring capabilities as MCP tools. It is designed to be added as an MCP server to compatible chat or development clients so they can programmatically interact with VisualPing’s monitoring features.

- **Type:** MCP server integration
- **Category:** Monitoring
- **Use cases:** Website monitoring, change detection, alerting
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Website change detection**
  - Integrates VisualPing’s core functionality for detecting changes on web pages.
- **Monitoring and alerting**
  - Provides tooling to set up and manage monitoring workflows and receive alerts when changes are detected (as exposed via MCP tools).
- **Static MCP server endpoint**
  - Uses a single static URL that works for all supported MCP clients: `https://mcp.pipedream.net/v2`.
- **Account-based authentication**
  - Authentication occurs when adding the MCP server to your application/client, allowing access to your VisualPing-related tools.
- **Client-agnostic integration**
  - Designed to be added to various MCP-compatible chat clients or applications; configuration instructions are provided per client.
- **Configuration documentation**
  - Central configuration page available for detailed setup steps (via the referenced Configuration page on the source site).

## Integration & Setup
1. **Connect account**
   - Connect your account in the Pipedream interface and select your client to begin configuration.
2. **Copy MCP server URL**
   - Use the static URL `https://mcp.pipedream.net/v2` as the MCP server endpoint.
3. **Add to your application**
   - Add the MCP server URL to your MCP-compatible chat client or app and complete authentication.
4. **Access tools**
   - Once configured, the MCP server exposes VisualPing-related tools (actions) for website change detection, monitoring, and alerting.

## Pricing
The provided content does not include any pricing or plan information for the VisualPing MCP Server or associated services.