# HumanLayer MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** HumanLayer  
**Source:** https://mcp.pipedream.com/app/humanlayer

## Overview
HumanLayer MCP Server provides an API and SDK that allow AI agents to contact humans for feedback, input, and approvals. It is exposed as a Model Context Protocol (MCP) server that can be added to compatible chat clients and applications via a static MCP endpoint.

## Features
- **Human-in-the-loop interactions**: Enables AI agents to reach out to human users to request feedback, additional input, or explicit approvals.
- **API and SDK access**: Provides programmatic interfaces (API and SDK) for integrating human feedback and approval flows into AI-powered applications.
- **MCP server integration**: Exposed as an MCP server so it can be used with MCP-compatible clients and tooling.
- **Static MCP server URL**: Uses a single static endpoint for all clients:  
  `https://mcp.pipedream.net/v2`
- **Client-agnostic configuration**: The same MCP URL works for every supported client; authentication is handled when the server is added to an application.
- **Configurable via chat clients**: Can be added to various chat clients that support MCP, with client-specific setup instructions available via the configuration documentation.

## Technical Details
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`
- **Authentication:** Performed when adding the MCP server to an application/client (details provided in configuration docs).
- **Configuration docs:** Additional setup and configuration information is available on the product’s Configuration page (linked from the source).

## Pricing
No pricing information is provided in the available content.