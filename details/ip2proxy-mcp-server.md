# IP2Proxy MCP Server

**Category:** Security & Attestation MCP Servers  
**Brand:** Pipedream  
**Slug:** `ip2proxy-mcp-server`

## Overview
IP2Proxy MCP Server exposes the IP2Proxy™ Proxy Detection Web Service through a Pipedream-hosted MCP endpoint. It allows MCP-compatible tools and chat clients to detect anonymous proxies, VPNs, TOR exit nodes, search engine robots, and residential proxies by IP address, and to retrieve associated IP location data when a proxy is detected.

**MCP Server URL:**
```text
https://mcp.pipedream.net/v2
```

## Features
- **Proxy / Anonymity Detection via IP**
  - Detects anonymous proxy usage by IP address
  - Identifies VPN endpoints
  - Identifies TOR exit nodes
  - Detects search engine robots (SES)
  - Detects residential proxies (RES)

- **IP Location Lookup (when proxy detected)**
  - Provides IP location lookup information associated with detected proxies

- **Web Service / API Access**
  - Hosted Web Service accessible via the MCP server
  - REST API interface
  - Supports JSON responses
  - Supports XML responses

- **MCP Integration**
  - Exposed via a static MCP server URL usable by multiple clients
  - Authentication performed when adding the server to a client/application
  - Designed to be integrated into chat clients and other MCP-aware tools

## Use Cases
- Security and fraud detection based on IP reputation
- Filtering or flagging traffic coming from proxies, VPNs, or TOR
- Differentiating human users from search engine robots
- Enriching security workflows with IP location data for detected proxies

## Pricing
The provided content does not list any pricing or plan details for IP2Proxy MCP Server.