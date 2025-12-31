# Eventbrite MCP Server

**Category:** Business & Commerce – MCP Servers  
**Brand:** Eventbrite  
**Source:** https://mcp.pipedream.com/app/eventbrite

## Overview
Eventbrite MCP Server integrates the Eventbrite event management and ticketing platform with the MCP ecosystem. It exposes Eventbrite operations (events, orders, attendees, and event creation) as standardized MCP tools so compatible clients and agents can manage Eventbrite data and workflows via a single MCP server endpoint.

## Key Details
- **Static MCP server URL:** `https://mcp.pipedream.net/v2`
- **Authentication:** Performed when adding the server to your MCP-compatible application / chat client.
- **Provider:** Pipedream (integrated into MCP as an Eventbrite server)

## Features
- **Unified MCP Endpoint**  
  - Use a single static URL (`https://mcp.pipedream.net/v2`) for all clients.  
  - Works across any supported MCP-compatible app or chat client.

- **Account Connection**  
  - Connect your Eventbrite account through Pipedream’s configuration flow.  
  - Manage authentication once, then reuse the same MCP server across clients.

- **Available Tools / Actions**  
  The server currently exposes 5 Eventbrite actions as MCP tools:
  1. **Get My Orders**  
     - Retrieve a list of event orders placed by the authenticated Eventbrite user.
  2. **Get Event Summary**  
     - Fetch a summary for a specified Eventbrite event.
  3. **Get Event Details**  
     - Retrieve detailed information for a specified event (more granular than summary).
  4. **Get Event Attendees**  
     - Get a list of attendees for a specified event.
  5. **Create Event**  
     - Create a new Eventbrite event programmatically via MCP.

- **Client-Agnostic Setup**  
  - Can be added to different chat clients or MCP applications.  
  - Configuration instructions are available per client via the Pipedream configuration page.

## Use Cases
- Build agents that:
  - Check the authenticated user’s Eventbrite orders.
  - Pull summaries or detailed info for specific events.
  - List or analyze attendees for an event.  
  - Create new events from within an MCP-compatible chat or automation environment.

## Pricing
No specific pricing information for the Eventbrite MCP Server is provided in the available content. Use may be subject to standard Pipedream and Eventbrite account limits or pricing.