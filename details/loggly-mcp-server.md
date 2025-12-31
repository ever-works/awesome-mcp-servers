# Loggly MCP Server

**Category:** Monitoring  
**Tags:** logging, observability, metrics

## Overview
Loggly MCP Server is an integration that allows MCP-based workflows and applications to send log data to the Loggly logging platform. It uses a static MCP server endpoint hosted by Pipedream, with separate Loggly credentials required to read or manage data in Loggly.

- **Name:** Loggly (Send Data) MCP Server  
- **Provider / Brand:** Loggly (via Pipedream Connect)  
- **Slug:** loggly-mcp-server  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Loggly data ingestion:** Sends log and event data from MCP workflows to the Loggly logging platform.
- **MCP integration:** Designed as an MCP server so it can be added to MCP-compatible chat clients and tools.
- **Static server endpoint:** Uses a single static MCP URL (`https://mcp.pipedream.net/v2`) that works for all supported clients.
- **Client-agnostic usage:** Same URL is used across different MCP-compatible chat clients and applications.
- **Authentication on add:** Authentication is performed when adding the server to your client or application, rather than using client-specific URLs.
- **Separation of concerns:** Sending data is handled via this MCP server, while reading or querying data in Loggly requires separate Loggly credentials and access.
- **Hosted by Pipedream Connect:** Operated as part of Pipedream’s MCP server infrastructure, inheriting its configuration model and operational environment.

## Integration & Configuration
- Add the server using the static MCP endpoint: `https://mcp.pipedream.net/v2`.
- Configure authentication when registering the server in your chat client or application.
- Further configuration details are available on the associated configuration page (via Pipedream Connect).

## Pricing
Pricing details for the Loggly MCP Server integration are not provided in the available content. Use of this integration may depend on:
- Your Loggly account and its pricing plan.
- Any applicable pricing or limits from Pipedream / Pipedream Connect.

For exact pricing, refer to Loggly and Pipedream official pricing pages.