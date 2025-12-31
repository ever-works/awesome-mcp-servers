# QuickBooks MCP Server

**Brand:** Pipedream  
**Category:** Finance / Market Data MCP Servers  
**Website:** https://mcp.pipedream.com/app/quickbooks  
**MCP Endpoint URL:** `https://mcp.pipedream.net/v2`

QuickBooks MCP Server is an MCP endpoint on Pipedream that exposes QuickBooks Online accounting and finance operations as tools for MCP-aware applications and assistants.

---

## Description

QuickBooks MCP Server connects MCP-aware applications to QuickBooks Online so they can manage accounting and bookkeeping data programmatically. After connecting a QuickBooks Online account and client, applications can call exposed actions (tools) over MCP to search, read, update, and send financial documents and entities such as invoices, estimates, customers, vendors, items, services, purchases, and more.

---

## Features

### MCP Integration
- Static MCP server URL: `https://mcp.pipedream.net/v2` (used for all clients).
- Authentication performed when adding the server to an MCP-aware application or chat client.
- Works as a QuickBooks Online backend for AI assistants and other MCP-compatible tools.

### QuickBooks Account Connection
- Sign-in flow to connect a QuickBooks Online account.
- Client selection after connection to operate on the correct QuickBooks company.

### Available Tools / Actions

The server exposes 41 QuickBooks actions as MCP tools. From the provided content, the following actions are explicitly listed:

- **Void Invoice**  
  Void an existing invoice in QuickBooks.

- **Update Item**  
  Update properties of an existing item (e.g., product/service details).

- **Update Invoice**  
  Modify an existing invoice’s fields (such as line items, amounts, or customer details).

- **Update Estimate**  
  Update an existing estimate.

- **Update Customer**  
  Change customer information stored in QuickBooks.

- **Sparse Update Invoice**  
  Perform a partial (sparse) update on an invoice:
  - Only specified fields in the request are updated.
  - Unspecified fields remain unchanged.
  - The invoice to update is identified by ID in the request body.

- **Send Invoice**  
  Send an invoice to a recipient via email.

- **Send Estimate**  
  Send an estimate to a recipient via email.

- **Search Vendors**  
  Search for vendors in QuickBooks based on specified criteria.

- **Search Time Activities**  
  Search time activity records.

- **Search Services**  
  Search for services defined in QuickBooks.

- **Search Query**  
  Run a general search query against a QuickBooks entity using QuickBooks’ query language.

- **Search Purchases**  
  Search purchase records.

- **Search Products**  
  Search for products defined in QuickBooks.

- **Search Items**  
  Search QuickBooks items (products/services) via filters or query.

- **Search Invoices**  
  Search invoice records (e.g., by customer, date, status, or other criteria).

> Note: The page states that **41 actions** are available as tools. Only the subset above is explicitly listed in the provided content; additional actions exist but are not detailed here.

---

## Configuration & Usage

- Copy the static MCP server URL (`https://mcp.pipedream.net/v2`).
- Add the server URL to an MCP-aware application or chat client.
- Authenticate with QuickBooks Online during setup.
- Use the configuration page (not included in the excerpt) for client-specific setup steps.

---

## Pricing

No pricing information is provided in the supplied content for QuickBooks MCP Server or its usage on Pipedream. Users should refer to the official Pipedream/QuickBooks MCP page for current pricing details.