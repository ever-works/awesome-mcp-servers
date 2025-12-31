# OnePageCRM MCP Server

## Overview
The OnePageCRM MCP Server is an integration endpoint that connects OnePageCRM—an action-focused CRM for small businesses—to MCP-compatible applications via Pipedream. It enables task- and action-oriented sales workflows to be accessed and automated from chat clients and other tools.

## Features
- **MCP server endpoint**: Provides a static MCP server URL (`https://mcp.pipedream.net/v2`) usable across clients.
- **Central configuration via Pipedream**: Configure the OnePageCRM integration within Pipedream’s interface.
- **Account connection**: Connect a OnePageCRM account to enable CRM-driven workflows.
- **Client selection**: Choose the target client/application that will use the MCP server.
- **Tool exposure**: Makes OnePageCRM-related actions and tools available to MCP-compatible chat clients (listed as “Available tools” once loaded).
- **Authentication flow**: Authentication occurs when adding the MCP server to your application, keeping the URL itself static and reusable.
- **Multi-client support**: Documentation/guidance provided for adding the server to different chat clients.

## Configuration
- **MCP Server URL**: `https://mcp.pipedream.net/v2`
- **Setup steps (high level)**:
  1. Connect your OnePageCRM account in Pipedream.
  2. Select the client (chat client or app) that will use the MCP server.
  3. Copy the static MCP server URL.
  4. Add the server URL to your application and authenticate.
  5. Load and use the available OnePageCRM tools/actions.
- Additional configuration details are available on Pipedream’s dedicated **Configuration** page.

## Pricing
No pricing information is provided in the available content. Refer to Pipedream and OnePageCRM official sites for any applicable costs related to the MCP server integration and CRM usage.