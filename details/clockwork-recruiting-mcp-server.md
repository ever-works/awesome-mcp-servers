# Clockwork Recruiting MCP Server

**Category:** Business & Commerce MCP Servers  
**Tags:** recruiting, ATS, HR

## Overview
Clockwork Recruiting MCP Server is an integration that exposes Clockwork Recruiting (executive search and recruiting software) over the Model Context Protocol (MCP). It allows AI agents and MCP-compatible chat clients to work with executive search and recruiting data hosted in Clockwork Recruiting.

## Features
- **MCP-compatible integration**: Provides an MCP Server endpoint that can be added to any compatible chat or AI client.
- **Access to executive search data**: Designed for working with executive search and recruiting information used by executive search firms, in-house recruiting teams, and venture capital organizations (specific tools and schema not detailed in the source content).
- **Static server URL**: Uses a single static MCP server URL for all clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic usage**: Can be added to different MCP-capable chat clients by following each client’s configuration instructions.
- **Authentication at connection time**: Authentication is performed when the MCP server is added in the client, rather than via per-user URLs.
- **Configuration documentation**: A full configuration page is available (via Pipedream) to guide setup and usage.

## Technical Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Provider:** Pipedream Connect (integration layer) with Clockwork Recruiting as the underlying recruiting platform.

## Pricing
No pricing information is provided in the available content.

## Links
- Source / App page: https://mcp.pipedream.com/app/clockwork_recruiting
- Configuration documentation: /configuration (on Pipedream)
- Pipedream Connect: https://pipedream.com/connect