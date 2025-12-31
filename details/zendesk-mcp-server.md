# Zendesk MCP Server

**Category:** Messaging MCP Servers  
**Tags:** customer-support, helpdesk, ticketing

## Overview
The Zendesk MCP Server exposes Zendesk’s customer service capabilities as Model Context Protocol (MCP) tools, allowing AI agents and chat-based applications to work with Zendesk tickets, users, macros, and knowledge base content.

- **Server URL:** `https://mcp.pipedream.net/v2`
- **Integration type:** MCP server backed by Zendesk via Pipedream
- **Use cases:** Managing support tickets, tags, custom fields, macros, user data, and articles from AI agents across email, chat, phone, mobile, and social channels.

## Features

### MCP Server & Configuration
- Static MCP server URL that works for any client: `https://mcp.pipedream.net/v2`.
- Authentication handled when adding the server to your MCP-compatible application.
- Works with multiple chat clients (added as a server in your chosen client).
- Central configuration available via a dedicated configuration page (external to this summary).

### Ticket Management Tools
- **Update Ticket**
  - Modify existing ticket properties via Zendesk’s API.
- **Delete Ticket**
  - Permanently remove a ticket from Zendesk (action referenced as available).
- **Get Ticket Info**
  - Retrieve detailed information for a specific ticket by ID.
- **List Tickets**
  - Fetch a list of tickets from Zendesk, useful for browsing or bulk operations.
- **Search Tickets**
  - Search tickets using Zendesk’s search API based on query parameters.

### Ticket Tag & Field Management
- **Set Ticket Tags**
  - Set tags on a ticket, replacing all existing tags with the provided set.
- **Remove Ticket Tags**
  - Remove specific tags from a ticket without replacing the entire tag set.
- **Set Custom Ticket Fields**
  - Set one or more custom field values on a ticket, enabling structured metadata and workflows.

### Comments & Conversation Data
- **List Ticket Comments**
  - Retrieve all comments for a specific ticket, enabling AI agents to read full conversation history.

### User Data
- **Get User Info**
  - Retrieve information about a specific Zendesk user (e.g., requester, agent) by ID.

### Macros & Automation
- **List Macros**
  - Retrieve all macros configured in Zendesk.
- **List Active Macros**
  - List all active shared and personal macros available to the current user.
- **Get Macro**
  - Retrieve a specific macro by its ID.

### Knowledge Base & Localization
- **List Articles**
  - Retrieve a list of knowledge base articles from Zendesk.
- **Get Article**
  - Retrieve a specific article by ID.
- **List Locales**
  - Retrieve all locales configured in the Zendesk instance, useful for language-aware responses.

### Tooling Summary
- 18 actions are available as tools in total (the page lists a subset explicitly), giving broad coverage over tickets, users, macros, articles, tags, locales, and comments.

## Pricing
No pricing information is provided in the referenced content. Use of this MCP server may depend on:
- Your existing Zendesk account/subscription, and
- Any applicable terms or pricing from the platform hosting the MCP server (Pipedream/Workday).