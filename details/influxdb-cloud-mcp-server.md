# InfluxDB Cloud MCP Server

## Overview
The InfluxDB Cloud MCP Server exposes InfluxDB Cloud—a serverless, scalable time series database platform—through the Model Context Protocol (MCP). It allows applications and chat-based clients to interact with InfluxDB Cloud running on major cloud providers (AWS, Azure, and Google Cloud) via a common MCP endpoint.

- **Name:** InfluxDB Cloud MCP Server
- **Provider / Brand:** InfluxData (via Pipedream Connect)
- **Category:** Database & Messaging MCP Servers
- **Tags:** time-series, cloud, database
- **MCP Endpoint URL:** `https://mcp.pipedream.net/v2`

## Features
- **Serverless time series database access**
  - Connects to InfluxDB Cloud, a serverless time series data platform.
  - Designed for time series workloads (metrics, events, monitoring data, etc.).

- **Scalable architecture**
  - Built to scale with time series workloads without manual capacity management (as described: "scalable, serverless time series platform").

- **Multi-cloud availability**
  - Available on major cloud providers:
    - AWS
    - Microsoft Azure
    - Google Cloud

- **Standard MCP server endpoint**
  - Uses a single static MCP server URL for all clients:
    - `https://mcp.pipedream.net/v2`
  - Authentication is handled when adding the server in the client/application.

- **Client-agnostic integration**
  - Can be added to different MCP-compatible chat clients or applications.
  - Configuration is documented via a central configuration page (referenced as a “full Configuration page”).

- **Delivered via Pipedream Connect**
  - Hosted and provided through Pipedream’s Connect platform, simplifying setup and integration.

## Configuration & Usage
- **MCP Server URL:**
  - Use `https://mcp.pipedream.net/v2` as the server URL when configuring the InfluxDB Cloud MCP Server in your client.
- **Authentication:**
  - Per the content, authentication occurs when the server is added to the application; specific auth methods are not detailed here.

## Pricing
The provided content does not include any pricing details or plan information for the InfluxDB Cloud MCP Server or InfluxDB Cloud. No pricing data can be listed based on the given source.