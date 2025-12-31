# Help Scout MCP Server

An MCP server that exposes Help Scout’s customer service and shared inbox platform to MCP-compatible agents, enabling programmatic access to conversations and support data.

## Overview
- **Type:** MCP server (integration/service)
- **Category:** Business & Commerce – MCP Servers
- **Platform:** Help Scout via Pipedream MCP
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Primary Use Case:** Programmatic management of Help Scout conversations, customers, and tags from MCP-compatible chat or agent applications.

## Features

### MCP Server & Configuration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable for all clients.
- Authentication performed when adding the server to an MCP-compatible application.
- Works with multiple chat / client applications (add the server to your preferred MCP-compatible app).

### Available Tools (Actions)
The Help Scout MCP Server exposes 8 actions as tools:

1. **Update Conversation**
   - Update an existing conversation in Help Scout.
   - Modify properties such as status or other conversation details (per underlying Help Scout API capabilities).

2. **Send Reply**
   - Send a reply to an existing conversation.
   - Triggers an actual email to the customer through Help Scout.

3. **List Tags**
   - Retrieve a list of all tags configured in Help Scout.
   - Useful for classification, routing, and reporting within automated agents.

4. **Get Tag by ID**
   - Fetch detailed information for a specific tag using its ID.

5. **Get Conversation Threads**
   - Retrieve the threads belonging to a specific conversation.
   - Allows agents to access the full message history / timeline of a case.

6. **Get Conversation Details**
   - Retrieve detailed data for a specific conversation.
   - Access metadata and structured information about a ticket/conversation.

7. **Create Customer**
   - Create a new customer record in Help Scout.
   - Enables automated customer onboarding or record creation from MCP workflows.

8. **Add Note to Conversation**
   - Add an internal note to an existing conversation.
   - Supports internal collaboration and automated annotations without emailing the customer.

## Pricing
Pricing information for the Help Scout MCP Server via Pipedream is not provided in the available content.