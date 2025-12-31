# Zoho Desk MCP Server

## Overview
Zoho Desk MCP Server is an MCP (Model Context Protocol) server integration that exposes Zoho Desk’s omnichannel customer service and ticketing capabilities to MCP-compatible applications. It allows agents and systems to work with tickets, contacts, and knowledge base content programmatically from within chat or other MCP-enabled clients.

- **Category:** Business & Commerce – MCP Servers
- **Use cases:** Customer support, ticketing workflows, omnichannel service, knowledge base access from chat/AI tools.

## Features

### MCP Server & Connectivity
- Static MCP server URL usable across clients: `https://mcp.pipedream.net/v2`.
- Connects a Zoho Desk account and client to expose tools inside MCP-compatible apps.
- Works with multiple chat or agent clients; configuration documented via a central configuration page.

### Ticket Management Tools
- **Update Ticket**: Modify details of an existing ticket (e.g., status, fields, assignments) via the `update-ticket` tool.
- **Search Ticket**: Search for tickets in the help desk using various criteria.
- **List Tickets**: List all tickets with optional filtering (e.g., by status, time, or other attributes).
- **Get Ticket Details**: Retrieve details of a specific ticket (metadata, status, etc.).
- **List Ticket Threads**: Retrieve a list of all threads associated with a given ticket.
- **Get Thread Details**: Access details of a specific thread belonging to a ticket.
- **List Ticket Attachments**: List attachments associated with a particular ticket.

### Contact Management Tools
- **Update Contact**: Update details of an existing contact.
- **Find or Create Contact**: Look up a contact by specified criteria and create one if it does not exist.

### Communication Tools
- **Send E-Mail Reply**: Send an email reply on a ticket directly through Zoho Desk.

### Knowledge Base & Help Center Tools
- **Search Articles**: Search knowledge base articles using query parameters.
- **List Root Categories**: List root knowledge base categories for a help center.
- **List Help Centers**: List help centers configured in a Zoho Desk organization.
- **List Articles**: List knowledge base articles for a specified help center.
- **Get Article**: Retrieve the details of a specific knowledge base article.

### Tooling Scope
- 21 total actions are exposed as tools (a subset is listed explicitly above), covering:
  - Ticket lifecycle operations
  - Contact operations
  - Email-based support communication
  - Knowledge base and help center navigation and retrieval

## Pricing
No pricing information is provided in the available content.