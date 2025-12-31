# Thanks.io MCP Server

## Overview
Thanks.io MCP Server is an MCP-based integration that allows applications and chat clients to send direct mail digitally via Thanks.io, including postcards, notecards, letters, and gift cards. It is hosted on Pipedream and can be added to any MCP-compatible client using a single static server URL.

- **Item type:** MCP server / integration
- **Category:** Business & Commerce MCP Servers
- **Brand:** Thanks.io
- **Source URL:** https://mcp.pipedream.com/app/thanks_io
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Server & Configuration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across all clients.
- Authentication handled when adding the server to an MCP-compatible application or chat client.
- Works within supported chat clients and tools that can consume MCP servers.
- Configuration instructions available via Pipedream’s configuration documentation.

### Direct Mail Sending Actions
The server exposes 9 actions as tools:

1. **Send Postcard**
   - Send a postcard to a specific recipient.
   - Uses Thanks.io’s postcard sending capabilities.

2. **Send Postcard via Radius Search**
   - Send postcards to multiple recipients discovered via a geographic radius search.
   - Useful for location-based campaigns.

3. **Send Notecard**
   - Send a notecard to an individual recipient.

4. **Send Notecard via Radius Search**
   - Send notecards to recipients identified within a geographic radius.

5. **Send Letter**
   - Send a letter to a specific recipient.

6. **Send Letter via Radius Search**
   - Send letters to multiple recipients within a defined geographic radius.

7. **Send Giftcard**
   - Send a gift card to a recipient through Thanks.io.

### Recipient & List Management
8. **Add Recipient**
   - Add a recipient to a mailing list in Thanks.io.

9. **Delete Recipient**
   - Remove a recipient from a mailing list.

### Use Cases
- Automating direct mail as part of marketing workflows.
- Running geographically targeted campaigns (radius-based search for postcards, notecards, and letters).
- Managing mailing lists programmatically from an MCP-enabled client or application.

## Pricing
No pricing information is provided in the available content. Users should refer to Thanks.io and/or Pipedream for current pricing and usage costs.