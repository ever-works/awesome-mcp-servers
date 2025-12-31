# Uber Direct MCP Server

## Overview
Uber Direct MCP Server is an MCP (Model Context Protocol) server integration that exposes Uber Direct’s on‑demand, white‑label delivery capabilities to MCP‑compatible applications via a single static endpoint. It is provided through Pipedream Connect.

- **Category:** Business & Commerce – MCP Servers
- **Provider/Brand:** Uber (via Pipedream)
- **Purpose:** Enable applications (e.g., AI/chat clients) to access Uber Direct delivery features through a unified MCP server URL.

## Features
- **MCP-based integration**: Access Uber Direct functionality through the Model Context Protocol, enabling tools and agents in MCP-compatible clients to interact with Uber Direct.
- **Static server URL**: A single, static MCP server endpoint that works for all clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic setup**: The same endpoint can be added to different chat or MCP-enabled clients; configuration is handled at the client level.
- **Authentication at client setup**: Authentication is performed when adding the server to each application/client, not by changing the server URL.
- **On-demand delivery access**: Designed to expose Uber Direct’s on-demand, white-label delivery capabilities (e.g., creating and managing deliveries) via MCP.
- **Brandable experience**: Supports white-label delivery, allowing the end-user experience to be branded by the integrating business rather than Uber.
- **Configuration documentation**: A dedicated configuration page is available to guide setup steps for different clients (via the “Configuration” link on Pipedream Connect).

## Technical Details
- **MCP server endpoint:** `https://mcp.pipedream.net/v2`
- **Integration platform:** Pipedream Connect
- **Usage context:** Added as an MCP server in compatible chat or agent clients, which then authenticate and call Uber Direct features.

## Pricing
The provided content does not include any pricing or plan information for the Uber Direct MCP Server or underlying Uber Direct services.

## Links
- Uber Direct MCP Server page: https://mcp.pipedream.com/app/uber_direct
- Configuration documentation: /configuration (from the Pipedream site)
- Terms: https://pipedream.com/terms
- Privacy Policy: https://pipedream.com/privacy