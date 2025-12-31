# Datadog MCP Server

**Category:** Monitoring  
**Brand:** Datadog  
**Slug:** `datadog-mcp-server`

## Description
The Datadog MCP Server is a model context protocol (MCP) server that allows agents and compatible chat clients to query and interact with Datadog’s cloud monitoring and observability services. It is delivered as a cloud monitoring service endpoint, intended to be added to MCP-compatible applications.

## MCP Server URL
- Static MCP server endpoint (works for all clients):
  - `https://mcp.pipedream.net/v2`
- Authentication is performed when you add the server to your application or client.

## Features
- **MCP-compatible server** for integrating Datadog monitoring and observability capabilities into MCP-aware applications and agents.
- **Single static server URL** usable across different clients, simplifying configuration and setup.
- **Cloud-based delivery**: operates as a cloud monitoring service endpoint rather than requiring local hosting.
- **Client-agnostic integration**: designed to work with multiple chat clients that support MCP.
- **Authentication on connection**: credentials or tokens are provided when adding the server to each application, keeping the URL itself static.

## Integration & Configuration
- Add the server by referencing the static URL `https://mcp.pipedream.net/v2` in your MCP-compatible client or application.
- Detailed integration steps and client-specific instructions are available via the platform’s configuration documentation ("Configuration" page referenced by the source site).

## Pricing
- No pricing information is provided in the available content.