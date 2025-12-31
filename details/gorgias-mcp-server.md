## Gorgias MCP Server

**Category:** Business & Commerce · MCP Servers  
**Tags:** customer-support, helpdesk, e-commerce

Gorgias MCP Server provides a Model Context Protocol (MCP) integration with the Gorgias ecommerce helpdesk platform, enabling AI/chat clients to interact with Gorgias customer support and ticket management data via a standardized server endpoint.

---

### MCP Endpoint
- **MCP server URL:** `https://mcp.pipedream.net/v2`  
  This is a static URL used to connect from compatible MCP-enabled applications. Authentication is performed when adding the server to the client application.

---

### Features

#### Integration & Configuration
- Connect a Gorgias account to an MCP-compatible chat client or application.
- Central configuration via the Pipedream Gorgias OAuth app (`https://mcp.pipedream.com/app/gorgias_oauth`).
- Works with multiple chat clients (selection/usage handled in the client’s configuration flow).

#### Ticket Management Tools
- **Create Ticket**  
  Create a new ticket in Gorgias (title, content, and other ticket fields as supported by the Gorgias API).
- **Update Ticket**  
  Modify attributes of an existing ticket (e.g., status, assignee, subject or other supported fields).
- **Get Ticket**  
  Retrieve details of a specific ticket by ID.
- **List Tickets**  
  List tickets from the Gorgias account (with filtering/pagination options as defined in the underlying action).

#### Ticket Fields & Tags
- **Update Ticket Field Values**  
  Update custom or standard field values for a specific ticket.
- **List Ticket Field Values**  
  Retrieve all field values associated with a particular ticket.
- **Set Ticket Tags**  
  Set or update tags on a specified ticket.
- **List Ticket Tags**  
  List all tags currently applied to a particular ticket.

#### Messages (Ticket Messages & Global Messages)
- **List Ticket Messages**  
  List all messages associated with a specific ticket (e.g., customer and agent replies).
- **Get Ticket Message**  
  Retrieve a specific message from a ticket by its identifier.
- **List Messages**  
  List messages across the account (not limited to a single ticket), as supported by the Gorgias API.

#### Customer Management
- **Retrieve a Customer**  
  Fetch customer details from Gorgias by ID or other supported lookup.
- **Update Customer**  
  Update stored customer information (e.g., name, contact details, or other profile fields).

#### Macros
- **List Macros**  
  List all macros defined in the Gorgias account.
- **Get Macro**  
  Retrieve a specific macro by ID.
- **Update Macro**  
  Update an existing macro (e.g., content, title, or configuration).
- **Delete Macro**  
  Remove a macro from the Gorgias account.

> In total, 21 actions are available as tools; only those explicitly listed in the provided content are enumerated above.

---

### Pricing
No pricing information is provided in the available content. Use of this MCP server may depend on:
- A Gorgias account and its associated plan, and
- Any terms or limits applied by the Pipedream integration.

For specific pricing or plan details, refer to Gorgias and/or Pipedream documentation and billing pages.