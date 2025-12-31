# IP2Location.io MCP Server

An MCP (Model Context Protocol) server that exposes IP2Location.io’s IP geolocation capabilities within compatible MCP clients.

---

## Overview
- **Type:** MCP server / data access integration
- **Purpose:** Query IP geolocation data for IP addresses from within MCP-enabled applications and chat clients.
- **Provider:** Pipedream (via Pipedream Connect)
- **Protocol:** MCP (Model Context Protocol)
- **Use cases:**
  - Resolve an IP address to a geographic location
  - Enrich logs or application events with IP-based location metadata
  - Build assistants or tools that need inline IP geolocation lookup

---

## Features
- **IP Geolocation Lookup**
  - Pinpoint the location of an IP address using IP2Location.io’s data.
  - Designed to be called directly from MCP-compatible chat or developer tools.

- **Static MCP Server Endpoint**
  - Single shared URL for all MCP clients:
    - `https://mcp.pipedream.net/v2`
  - Works across supported MCP clients without per-client URL changes.

- **MCP Client Integration**
  - Can be added as an external tool/server in MCP-enabled chat applications.
  - Uses your chosen client’s standard MCP configuration flow.

- **Centralized Configuration Documentation**
  - Detailed connection and configuration instructions available via Pipedream’s **Configuration** page (covers adding the server to different clients).

- **Hosted & Managed by Pipedream**
  - Runs as a hosted MCP server on Pipedream’s infrastructure.
  - No separate server deployment required by the user.

---

## Technical Details
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`
- **Authentication:** Performed when adding the MCP server to the client (details provided in client-specific setup docs on Pipedream).
- **Category / Domain:**
  - IP data
  - Geolocation
  - API-based data access

---

## Pricing
The provided content does not include pricing information for the IP2Location.io MCP Server. Consult the linked Pipedream / IP2Location.io pages for current pricing and plan details.