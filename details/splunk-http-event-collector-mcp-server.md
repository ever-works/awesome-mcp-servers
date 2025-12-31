# Splunk HTTP Event Collector MCP Server

**Category:** Monitoring  
**Brand:** Splunk  
**Slug:** splunk-http-event-collector-mcp-server  
**Tags:** logs, observability, metrics

## Description
The Splunk HTTP Event Collector (HEC) MCP Server integrates Splunk’s HTTP Event Collector with MCP-compatible clients, allowing applications and tools to send log and event data to Splunk Enterprise or Splunk Cloud over HTTP/HTTPS.

## Features
- **MCP Server integration**: Exposes Splunk HEC capabilities through an MCP-compatible server endpoint.
- **HTTP/HTTPS data ingest**: Supports sending logs and event data to Splunk Enterprise and Splunk Cloud using standard HTTP or HTTPS.
- **Static MCP endpoint**: Uses a single static MCP server URL for all clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic connection**: Designed to work with multiple MCP-aware chat clients and applications.
- **Authentication at client setup**: Authentication is handled when adding the server to your application or client.

## Usage
- Copy the MCP server URL `https://mcp.pipedream.net/v2`.
- Add this MCP server to your MCP-compatible client or application.
- Configure authentication and any Splunk HEC details as directed by your client’s configuration flow.

## Pricing
Pricing details are not provided in the available content.