# Microsoft Outlook Calendar MCP Server

**Brand:** Microsoft  
**Category:** Workflow Automation MCP Servers  
**Tags:** calendar, scheduling, microsoft-365

## Overview
The Microsoft Outlook Calendar MCP Server exposes Outlook Calendar functionality to MCP-compatible clients, enabling access to calendar and scheduling features that are integrated with Outlook email and contacts. It connects via a static MCP server URL and allows authenticated clients to manage calendar events and availability.

## Features
- **MCP Server Endpoint**
  - Single static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
  - Authentication occurs when adding the server to an MCP-compatible application.

- **Outlook Calendar Integration**
  - Operates on the user’s default Outlook calendar.
  - Works within the broader Microsoft 365 environment, integrated with email, contacts, and other Outlook features.

- **Available Tools (Actions)**
  - **Create Calendar Event**
    - Create a new event in the user’s default calendar.
  - **Update Calendar Event**
    - Modify an existing event in the user’s default calendar.
  - **Delete Calendar Event**
    - Remove an event from the user’s default calendar.
  - **List Events**
    - Retrieve a list of event objects in the user’s mailbox.
  - **Get Free/Busy Schedule**
    - Obtain free/busy availability information for:
      - Individual users
      - Distribution lists
      - Resources such as rooms or equipment
    - For a specified time period.

- **Client Integration**
  - Can be added to various MCP-compatible chat or AI clients.
  - Configuration guidance is available via a dedicated configuration page (not client-specific in the content).

## Configuration
- Use the static MCP server URL `https://mcp.pipedream.net/v2` when adding the server to your MCP client.
- Authenticate with your Microsoft Outlook Calendar account during setup in the client.

## Pricing
- No pricing information is provided in the available content.