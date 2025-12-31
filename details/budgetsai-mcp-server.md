# Budgets.ai MCP Server

## Overview
Budgets.ai MCP Server is an MCP-compatible service that connects AI-powered budget identification and prediction capabilities from Budgets.ai into MCP-based applications. It is designed to help sales and marketing teams discover and forecast relevant budgets directly within their chat or MCP clients.

## Features
- **Generative AI-driven budgeting**: Uses artificial intelligence to identify and predict budgets relevant to sales and marketing activities.
- **Sales and marketing focus**: Tailored to support sales and marketing teams in planning and targeting by exposing budget insights via MCP tools.
- **MCP server endpoint**: Provides a static MCP server URL (`https://mcp.pipedream.net/v2`) that works for all clients.
- **Account-based configuration**: Users connect their Budgets.ai account and select the appropriate client context before use.
- **Authentication on connect**: Authentication occurs when adding the MCP server to the application, rather than requiring different URLs per client.
- **Multi-client compatibility**: Can be added to different chat clients or MCP-compatible applications using the same server URL.
- **Tool exposure via MCP**: Exposes Budgets.ai capabilities as “available tools” within the MCP environment (actions/tools are dynamically loaded by the MCP client).

## Integration & Setup
- **Static MCP URL**: `https://mcp.pipedream.net/v2`
- **Configuration flow**:
  - Connect a Budgets.ai account.
  - Select the relevant client/workspace.
  - Copy the MCP server URL.
  - Add the server to the chosen chat client or MCP-compatible application.
- **Configuration reference**: Additional setup details are provided on the platform’s configuration page (linked from the UI).

## Pricing
No pricing information is provided in the available content.