# Livestorm MCP Server

**Category:** Business & Commerce · MCP Servers  
**Brand:** Livestorm  
**Source:** https://mcp.pipedream.com/app/livestorm

## Overview
Livestorm MCP Server is an MCP Server integration that exposes Livestorm’s video engagement and webinar platform capabilities as tools within MCP-compatible applications. It lets you manage Livestorm events, sessions, and attendees programmatically via a static MCP server URL.

## Features

### MCP Server Setup
- **Static MCP server URL**: `https://mcp.pipedream.net/v2` (used for all clients; authentication handled when adding the server to your application).
- **Client-agnostic**: Designed to be added to various chat or MCP-compatible clients.
- **Configuration guidance**: Linked configuration page for detailed setup instructions.

### Available Tools (Actions)
The Livestorm MCP Server exposes 7 actions as MCP tools:

1. **Create Event**
   - Create a new Livestorm event.
   - Supports specifying full event attributes (e.g., title, schedule, description, etc. per Livestorm’s API model).

2. **Update Event**
   - Update an existing event using its full list of attributes.
   - Enables modifying event details such as metadata, scheduling, and configuration.

3. **Get Event**
   - Retrieve a single event by its identifier.
   - Useful for fetching event details for display or further automation.

4. **List Events**
   - List all events in a Livestorm workspace.
   - Allows browsing or programmatically iterating over existing events.

5. **List Sessions**
   - List all sessions associated with events.
   - Enables session-level operations or analytics within your workflows.

6. **Register Someone For A Session**
   - Register a participant (external registrant or internal team member) for a specific session.
   - Handles attendee enrollment via MCP without using the Livestorm UI directly.

7. **List Attendees From Event**
   - List all people linked to all the sessions of a given event.
   - Useful for attendance tracking, follow-up workflows, or reporting.

## Technical Context
- **Integration host**: Provided by Pipedream as an MCP Server endpoint.
- **Primary domain**: Video engagement, webinars, and event management via Livestorm.

## Pricing
No pricing or plan information is provided in the available content. Use of this MCP server may be subject to Pipedream and/or Livestorm account requirements and billing, as defined on their respective platforms.