# Google Analytics MCP Server

**Category:** Business & Commerce – MCP Servers  
**Brand:** Google  
**Source:** https://mcp.pipedream.com/app/google_analytics

## Overview
The Google Analytics MCP Server exposes Google Analytics data and reporting capabilities to MCP-compatible clients, allowing you to query and manage web and app analytics directly from your applications or chat clients.

It supports measurement and reporting on user activity across websites, web and mobile apps, and internet-connected devices.

## MCP Server URL
- Base MCP server URL: `https://mcp.pipedream.net/v2`
- This static URL is used for all clients; authentication occurs when adding the server to your application.

## Features
- **Google Analytics integration**
  - Connect a Google Analytics account and manage linked clients.
  - Measure and report on user activity across sites, apps, and connected devices.

- **MCP compatibility**
  - Exposes Google Analytics operations as tools/actions for MCP clients.
  - Can be added to supported chat clients and applications via a standard MCP server URL.

- **Available tools / actions (4 actions)**
  1. **Run Report (Universal Analytics / general reporting)**
     - Returns report metrics for a specified start and end date.
     - Enables querying analytics data based on time ranges.
  2. **Run Report in GA4**
     - Returns a customized report of Google Analytics 4 event data.
     - Provides statistics derived from data collected by the GA tracking code.
     - Supports event-based reporting in GA4 properties.
  3. **Create Key Event**
     - Creates a new key event in Google Analytics 4.
     - Useful for tracking critical user interactions or conversion events.
  4. **Create GA4 Property**
     - Creates a new Google Analytics 4 property.
     - Helps programmatically set up new GA4 properties from within MCP clients.

- **Configuration support**
  - Sign-in flow to connect a Google Analytics account.
  - Central configuration page (on Pipedream) for managing server setup and client connections.

## Pricing
The provided content does not include any pricing information for the Google Analytics MCP Server. Pricing details, if any, would need to be obtained from the source site or provider directly.