# Setmore MCP Server

Setmore MCP Server exposes Setmore’s online scheduling platform over MCP, enabling AI agents and MCP-compatible clients to manage appointments, calendars, and customer bookings programmatically.

**Website:** https://mcp.pipedream.com/app/setmoreappointments  
**MCP Server URL:** `https://mcp.pipedream.net/v2`

---

## Overview

Setmore MCP Server is an MCP (Model Context Protocol) endpoint, provided via Pipedream, that connects to Setmore’s online scheduling system. It allows applications and agents to interact with Setmore’s appointment and calendar features through a standardized MCP interface.

---

## Features

- **MCP-based access to Setmore**  
  - Exposes Setmore’s online scheduling platform over the MCP protocol.  
  - Compatible with any MCP-capable chat or agent client.

- **Appointment & booking management (via Setmore)**  
  - Programmatic management of appointments.  
  - Customer booking operations (create, update, and manage bookings) via Setmore’s scheduling capabilities.  
  - Calendar-related operations backed by Setmore’s calendar system.

- **Single static MCP endpoint**  
  - Uses a single static server URL: `https://mcp.pipedream.net/v2`.  
  - Same URL works for every MCP client; authentication is handled when adding the server to a specific application.

- **Client-agnostic integration**  
  - Can be added to different MCP-enabled chat clients and applications.  
  - Configuration is managed per client using the same MCP server URL.

- **Pipedream-hosted infrastructure**  
  - Hosted and provided via Pipedream Connect.  
  - Centralized management of the MCP server endpoint (terms and privacy managed by Pipedream).

---

## Authentication & Configuration

- Authentication is performed when you add the MCP server to your application/client.  
- A single MCP endpoint (`https://mcp.pipedream.net/v2`) is used; credentials / configuration are client-specific.  
- Additional configuration details are available on Pipedream’s Configuration page (not included here).

---

## Pricing

- The provided content does not specify any pricing details or plan tiers for the Setmore MCP Server or its usage via Pipedream.
