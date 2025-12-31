# Workbooks CRM MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Workbooks  
**Source:** https://mcp.pipedream.com/app/workbooks_crm

## Overview
Workbooks CRM MCP Server exposes core Workbooks CRM capabilities to MCP-compatible clients, enabling end-to-end CRM workflows for small and mid-size businesses via a standard MCP server endpoint.

- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Use case focus:** CRM for small and mid-size businesses
- **Typical records managed:** people (contacts, employees), organisations (customers, suppliers, partners, competitors), and customer orders.

## Features

### MCP Integration
- Single static MCP server URL usable across all clients; authentication handled when adding the server to an application.
- Can be added to various MCP-compatible chat or automation clients using a standard configuration flow.

### CRM Data Management Tools (Actions)
The server exposes 5 actions as tools:

1. **Update Person**
   - Update an existing person record in Workbooks CRM.
   - Supports managing data for contacts, employees, and similar person entities.

2. **Find or Create an Order**
   - Looks up an existing order; if none is found, creates a new order.
   - Useful for idempotent order operations from MCP clients.

3. **Create Person**
   - Create a new person record in the CRM.
   - Intended for storing contacts, employees, or other individual records in the database.

4. **Create Organisation**
   - Create a new organisation record (e.g., customers, suppliers, partners, competitors).
   - Supports building and maintaining company-level CRM data.

5. **Create Customer Order**
   - Create an order from customers for goods or services.
   - Enables MCP clients to initiate and record sales transactions directly in Workbooks CRM.

## Configuration
- Connect a Workbooks CRM account through the provided interface, then select the appropriate client to begin using the tools.
- Additional setup and client-specific configuration instructions are available on the platform’s configuration page.

## Pricing
- No pricing information is provided in the available content.