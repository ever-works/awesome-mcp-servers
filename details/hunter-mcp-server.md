# Hunter MCP Server

MCP Server integration for Hunter, exposing professional email verification and related operations via MCP endpoints.

- **Website / Source**: https://mcp.pipedream.com/app/hunter
- **Category**: Business & Commerce – MCP Servers
- **Tags**: email, verification, lead-generation
- **MCP Server URL**: `https://mcp.pipedream.net/v2`

---

## Description

Hunter MCP Server provides a Model Context Protocol (MCP) integration for the Hunter platform. It exposes Hunter’s email verification, email discovery, enrichment, and lead management capabilities as tools that can be called from compatible chat or MCP-enabled applications.

---

## Features

### MCP Integration
- Static MCP server endpoint (`https://mcp.pipedream.net/v2`) usable across clients.
- Authentication handled when adding the server to an MCP-compatible application.
- Works with multiple chat / MCP clients via configuration in your app.

### Email Verification & Discovery
- **Email Verifier**
  - Checks the deliverability of a given email address.
  - Verifies whether the email address exists in Hunter’s database.
  - Returns available sources for the email.

- **Email Finder**
  - Finds the most likely professional email address from:
    - Domain name
    - First name
    - Last name

- **Email Count**
  - Retrieves the number of email addresses Hunter has for a given domain or company.

- **Domain Search**
  - Searches all email addresses associated with a specific website or company.

### Lead Management
- **Create Lead**
  - Creates a new lead in your Hunter account.

- **Update Lead**
  - Updates an existing lead’s details by ID.

- **Get Lead**
  - Retrieves a single lead from your Hunter account by ID.

- **Delete Lead**
  - Deletes an existing lead from your Hunter account.

- **List Leads**
  - Lists all leads in your Hunter account.
  - Supports comprehensive filtering options.
  - Returns leads in sorted order, with the most recent first.

### Lead Lists
- **List Leads Lists**
  - Lists all lead lists in your Hunter account.
  - Results are sorted with the most recent lead lists first.

- **Get Leads List**
  - Retrieves all fields of a specific leads list.
  - Includes the leads contained within that list.

### Enrichment & Account Data
- **Combined Enrichment**
  - Returns all information associated with an email address and its domain name.

- **Account Information**
  - Retrieves information about your Hunter account (e.g., account-level metadata as exposed by Hunter’s API).

---

## Integration & Configuration

- Connect a Hunter account through the Pipedream-based MCP server.
- Use the static MCP server URL in compatible clients; authenticate during setup.
- Additional client-specific setup details are available via the configuration page linked from the source.

---

## Pricing

- No pricing information is provided in the available content for this MCP server or its usage.
