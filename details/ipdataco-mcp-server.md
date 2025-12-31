# ipdata.co MCP Server

## Overview
The ipdata.co MCP Server is an MCP integration that enriches IP addresses with detailed data, including location, company, carrier, and threat-related information, accessible via a static MCP server URL.

- **Category:** Security / MCP Servers
- **Provider / Brand:** ipdata.co
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### IP Enrichment
- Enriches IP addresses with:
  - Geolocation data (country, region, city, etc.)
  - Company-related information associated with the IP (where available)
  - Carrier information for mobile IPs
  - Threat-related data for security and risk use cases

### Available Tools / Actions
The MCP server exposes three primary HTTP-based tools:

1. **GET /{ip_address} — IP Lookup**
   - Performs a lookup for a specific IP address.
   - Returns enriched IP data, including location and other associated metadata.

2. **GET /time_zone/{ip_address} — Time Zone Detection**
   - Provides detailed and accurate time zone data for a given IP address.
   - Time zone information is adjusted for Daylight Saving Time (DST) where applicable.
   - Based on ipdata.co’s timezone detection capabilities.

3. **GET /carrier/{ip_address} — Mobile Carrier Detection**
   - Looks up the mobile carrier associated with an IP address.
   - Uses ipdata’s carrier database, covering:
     - 2,500+ mobile carriers
     - Across 234 countries

### MCP Integration & Configuration
- Uses a **single static MCP server URL** (`https://mcp.pipedream.net/v2`) that works for every supported client.
- Authentication is handled when adding the server to your client/application.
- Can be added to compatible chat or MCP-enabled clients as a remote tools provider.
- Configuration details are available via the Pipedream configuration page (per the source site).

## Pricing
No pricing information is provided in the available content. Use of ipdata.co or Pipedream services may be subject to their own pricing and terms outside this description.