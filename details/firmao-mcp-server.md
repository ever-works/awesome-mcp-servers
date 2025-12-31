# Firmao MCP Server

## Overview
The Firmao MCP Server is an MCP (Model Context Protocol) integration for the Firmao CRM platform. It exposes customer relationship management and sales opportunity data so MCP-compatible tools and agents can access and act on CRM information from a single endpoint.

## Features
- **Unified CRM data access**: Provides a single MCP endpoint to access Firmao CRM data and sales opportunities.
- **Sales opportunity management**: Surfaces opportunities originating from multiple channels, including:
  - Email/mailing
  - Cold calling
  - Live chat
  - Google Ads
  - Facebook
  - Callback requests
- **Centralized pipeline view**: Brings leads and opportunities from various sources into one place for MCP tools and agents.
- **Static MCP server URL**: Uses a single static URL (`https://mcp.pipedream.net/v2`) that works for all clients, simplifying configuration.
- **Authentication at client level**: Authentication occurs when adding the MCP server to an application, allowing secure per-client access.
- **Compatible with multiple chat clients**: Can be added to different MCP-enabled chat clients / applications (instructions vary by client).

## Technical Details
- **MCP server URL**: `https://mcp.pipedream.net/v2`
- **Integration type**: MCP server for Firmao CRM, hosted via Pipedream.
- **Data domains exposed**:
  - Customer relationship data
  - Sales opportunity / lead data from multiple acquisition channels

## Pricing
The provided content does not include any pricing or plan information for the Firmao MCP Server integration.