# AWeber MCP Server

MCP Server implementation for AWeber that exposes email marketing, campaigns, and subscriber management functionality via Pipedream.

---

## Overview
- **Type:** MCP server (tools / actions)
- **Category:** Business & Commerce – MCP Servers
- **Provider / Host:** Pipedream
- **Integrates with:** AWeber (email marketing platform)
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

The server lets MCP-compatible clients interact with AWeber accounts, lists, subscribers, and broadcasts through a standardized tool/action interface.

---

## Features

### MCP Server & Configuration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across clients
- Authentication handled when adding the server to an MCP-compatible application
- Usable from multiple chat / MCP clients (configured per client)

### Available Tools (Actions)
The AWeber MCP Server currently exposes **7 actions** as tools:

1. **Update Subscriber**
   - Update subscriber information identified by email
   - Operates on an existing subscriber record

2. **Get Subscribers**
   - Retrieve a paginated collection of subscribers
   - Filtered by specified AWeber account and list
   - Supports paging through large subscriber sets

3. **Get Lists**
   - Retrieve a paginated collection of subscriber lists
   - Useful for discovering available lists and their identifiers

4. **Get Accounts**
   - Retrieve a paginated collection of AWeber accounts
   - Enables selection/management of the correct account context

5. **Create Or Update Subscriber**
   - Create a new subscriber if the provided email does not exist
   - If the email exists, update that subscriber’s information
   - Combines “create” and “update” behavior for simpler workflows

6. **Create Broadcast**
   - Create an email broadcast under a specified account and list
   - Intended for sending campaign-style messages to list subscribers

7. **Add Subscriber**
   - Add subscribers to a specified account and list
   - Designed for straightforward list growth / opt-in handling

---

## Use Cases
- Manage AWeber subscribers directly from MCP-enabled chat or agent clients
- Sync external systems with AWeber lists (create/update subscribers)
- Browse and select accounts, lists, and subscribers programmatically
- Trigger and configure email broadcasts as part of automated workflows

---

## Pricing

No pricing information is provided in the available content for this MCP server or its usage via Pipedream. Pricing, if any, would depend on AWeber and/or Pipedream plans and is not specified here.