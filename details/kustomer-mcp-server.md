# Kustomer MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Kustomer  
**Source:** https://mcp.pipedream.com/app/kustomer

## Description
Kustomer MCP Server connects the Kustomer AI-powered customer service CRM to the Model Context Protocol (MCP), enabling MCP-compatible clients to access and manage Kustomer customer data and service workflows through a unified interface.

## MCP Server URL
- Base MCP server URL (static for all clients): `https://mcp.pipedream.net/v2`

## Features
- **Unified MCP Integration**
  - Exposes Kustomer CRM operations as MCP tools for use in compatible chat or agent clients.
  - Single static server URL for all clients, with authentication handled when adding the server to each application.

- **Customer Management Tools**
  - **Create Customer**: Create new customer records in Kustomer.
  - **Update Customer**: Update existing customer records.

- **Conversation Management Tools**
  - **Create Conversation**: Create new conversations in Kustomer.
  - **Update Conversation**: Update existing conversations.

- **Custom Object Management Tools**
  - **Get Custom Objects**: Retrieve multiple custom objects from Kustomer.
  - **Get Custom Object by ID**: Fetch a specific custom object by its internal ID.
  - **Get Custom Object by External ID**: Fetch a specific custom object using an external identifier.
  - **Update Custom Object by ID**: Update a custom object identified by its internal ID.

- **Tooling Overview**
  - 8 MCP tools/actions exposed for interacting with Kustomer resources (customers, conversations, and custom objects).

- **Client Setup Guidance**
  - Workflow to select a chat client and follow tailored instructions for adding the server.
  - Reference to a full configuration page for detailed setup steps.

## Usage Notes
- Requires signing in and connecting a Kustomer account within Pipedream.
- Authentication is performed when adding the MCP server to the chosen client/application.

## Pricing
- No pricing information is provided in the available content.