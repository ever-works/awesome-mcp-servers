# Segment MCP Server

**Category:** Data Access & Integration – MCP Servers  
**Brand:** Segment / Pipedream  
**Source:** https://mcp.pipedream.com/app/segment

## Overview
Segment MCP Server is an MCP (Model Context Protocol) server that connects to Segment’s customer data platform from compatible chat or AI clients. It exposes key Segment tracking and identification capabilities as tools so you can collect, unify, and route customer data (events, page views, traits, identities) directly through your application.

## Features

### MCP Server & Configuration
- **Static MCP Server URL:** Uses a single static endpoint `https://mcp.pipedream.net/v2` for all clients.
- **Client-Agnostic Setup:** The same URL works across supported chat / AI clients; authentication occurs when you add the server to your application.
- **Account Connection:** Sign in to connect your Segment account and select the desired client configuration.
- **Configuration Resources:** Guidance available via a dedicated configuration page for adding the server to various clients.

### Available Tools (Actions)
The server exposes 6 Segment actions as tools:

1. **Track – Record User Actions**  
   - Records discrete actions (events) that users perform.  
   - Requires either `userId` or `anonymousId`.  
   - Accepts additional event properties in line with Segment’s `track` API.

2. **Screen – Record Screen Views (Mobile)**  
   - Records when a user sees a screen in a mobile app.  
   - Requires `userId` or `anonymousId`.  
   - Supports sending screen-related metadata according to Segment’s `screen` method.

3. **Page – Record Page Views (Web)**  
   - Records page views on websites.  
   - Requires `userId` or `anonymousId`.  
   - Can include optional information such as page name, URL, and other page properties via Segment’s `page` method.

4. **Identify – Identify Users & Record Traits**  
   - Ties a user to their actions and records traits about them.  
   - Uses a unique `userId` and supports optional user traits (e.g., name, email, plan).  
   - Requires `userId` or `anonymousId`.

5. **Group – Associate Users with Groups**  
   - Associates an identified user with a group (e.g., account, organization, company).  
   - Requires `userId` or `anonymousId`.  
   - Supports group-level traits through Segment’s `group` method.

6. **Alias – Associate One Identity with Another**  
   - Links two identities (e.g., anonymous user to a known user after signup).  
   - Helps consolidate historical data under a single user identity using Segment’s `alias` method.

## Use Cases
- Collecting and sending event data to Segment from chat/AI environments.  
- Tracking web page views and mobile screen views via an MCP-enabled client.  
- Managing user identities, traits, and group associations from within an AI assistant or other MCP-compatible tools.  
- Unifying anonymous and authenticated identities using aliasing.

## Pricing
No pricing information is provided in the available content.