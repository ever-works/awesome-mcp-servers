# Expensify MCP Server

An MCP server integration for Expensify that exposes expense tracking, reporting, and policy management capabilities via MCP.

- **Website:** https://mcp.pipedream.com/app/expensify
- **Category:** Business & Commerce · MCP Servers
- **Tags:** expenses, receipts, accounting
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL that works for every client, with authentication handled when adding the server to your application.
- Can be added to compatible chat or MCP-enabled clients for conversational access to Expensify functions.

### Available Tools / Actions
1. **List Policies**
   - Retrieve a list of Expensify policies.
   - Useful for reviewing or selecting policies for expense processing or configuration.

2. **Export Report**
   - Export Expensify reports to a file.
   - Supported formats: **CSV**, **XLS**, **XLSX**, **TXT**, **PDF**, **JSON**, **XML**.
   - Enables external analysis, archiving, or sharing of expense data.

3. **Export Report to PDF**
   - Export a specific Expensify report directly to **PDF**.
   - Suitable for human-readable summaries or formal documentation.

4. **Create Report**
   - Create a new report containing transactions in a user’s Expensify account.
   - Supports building expense reports programmatically via MCP.

5. **Create Expense**
   - Create a new expense in Expensify.
   - Forms the basis for automated expense logging and tracking workflows.

### Expense & Preaccounting Automation (via Expensify capabilities)
- Leverages Expensify’s core capabilities through MCP, including:
  - Expense tracking.
  - Receipt scanning (via Expensify app, exposed through automated workflows).
  - Mileage tracking.
  - Fast reimbursement workflows (e.g., next-day reimbursement where enabled in Expensify).

## Pricing

No specific pricing details for the Expensify MCP Server are provided in the available content. Use of this server may be subject to:
- Pipedream platform pricing, and
- Expensify account / plan requirements.

Refer to the respective Pipedream and Expensify sites for current pricing information.