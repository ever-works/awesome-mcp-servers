# sevDesk MCP Server

## Overview
sevDesk MCP Server is an MCP integration that connects sevDesk billing and accounting software to MCP-compatible agents and chat clients. It enables freelancers, founders, startups, and small businesses to automate key invoicing and bookkeeping tasks directly via tools exposed by the server.

- **Category:** Business & Commerce – MCP Servers  
- **Provider / Brand:** sevDesk (via Pipedream)  
- **Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL that works for all clients (`https://mcp.pipedream.net/v2`).
- Authentication handled when adding the server to your MCP-compatible application or chat client.
- Usable across different chat clients / agents that support MCP.

### Available Tools / Actions
The sevDesk MCP Server currently exposes 6 actions as tools:

1. **Send Invoice Email**  
   - Sends an existing invoice via email from sevDesk.  
   - Uses an invoice stored in sevDesk and dispatches it to the specified recipient.

2. **Get Invoices**  
   - Retrieves multiple invoices from sevDesk.  
   - Supports optional filtering parameters such as:  
     - Invoice status  
     - Invoice number  
     - Date range  
     - Contact / customer

3. **Get Invoice**  
   - Finds and retrieves a single invoice by its ID.  
   - Useful for accessing full details of a specific invoice.

4. **Create Invoice**  
   - Creates a new invoice in sevDesk.  
   - Supports optional details including:  
     - Invoice date  
     - Due date  
     - Discount amount  
     - Invoice items / line items

5. **Create Contact**  
   - Creates a new contact (e.g., customer or client) in sevDesk.  
   - Intended for managing customer data used in invoicing and billing.

6. **Cancel Invoice**  
   - Cancels an existing invoice in sevDesk.  
   - Allows agents to void or revoke invoices programmatically.

## Use Cases
- Automating invoice creation and sending from a chat-based workflow.
- Retrieving and reviewing invoice lists based on status, date, or customer filters.
- Managing customer/contact records from within an MCP-enabled assistant.
- Canceling invoices through automated rules or conversational commands.

## Pricing
No pricing information is provided in the available content for the sevDesk MCP Server integration. Pricing, if any, would depend on sevDesk and/or Pipedream plans and is not specified here.