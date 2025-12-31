# Sendcloud MCP Server

**Category:** Business & Commerce – MCP Servers  
**Website:** https://mcp.pipedream.com/app/sendcloud  
**MCP Server URL:** `https://mcp.pipedream.net/v2`

An MCP server that connects MCP-compatible clients to Sendcloud’s shipping automation platform, allowing you to automate and manage shipping workflows (parcels, returns, shipping methods, service points, and more) across European carriers.

---

## Features

### MCP Integration
- Static MCP server endpoint (`https://mcp.pipedream.net/v2`) usable from any compatible client.
- Authentication handled when adding the server to your MCP-enabled application.
- Works with multiple chat / MCP clients; configuration guidance available via a central configuration page.

### Shipping & Logistics Tools (Actions)
23 actions are exposed as tools via the MCP server, including:

#### Returns
- **Validate Return** – Validate a return against Sendcloud’s rules and data.
- **List Returns** – List existing returns associated with your account.
- **Get Return** – Retrieve a specific return by ID.
- **Get Return Portal Settings** – Retrieve configuration/settings for the return portal.

#### Parcels
- **Update a Parcel** – Update parcel information under your API credentials.
- **List Parcels** – Retrieve a list of all parcels available under your API credentials.
- **List Parcel Statuses** – List possible or current parcel statuses.
- **List Parcel Documents** – List documents associated with parcels (e.g., labels, customs docs).

#### Shipping Methods
- **List Shipping Methods** – List available shipping methods.
- **Get Shipping Method** – Retrieve detailed information on a shipping method by ID.

#### Service Points
- **List Service Points** – List available service points (e.g., pickup locations).
- **List Service Point Carriers** – List carriers that support service points.
- **Get Service Point** – Retrieve a specific service point by ID.

#### Sender Addresses
- **List Sender Addresses** – List sender addresses associated with the authenticated user.
- **Get Sender Address** – Retrieve a specific sender address by ID.

#### Integrations & Shipments
- **List Integration Shipments** – List shipments created via integrations.

> Note: The site states there are **23 actions** available; only the actions explicitly listed in the provided content are detailed above.

---

## Typical Use Cases
- Automating parcel creation and updates from within an MCP-enabled chat or agent environment.
- Querying shipping methods, service points, and carriers to power shipping selection workflows.
- Managing returns (validation, retrieval, and configuration) directly via tools.
- Centralizing shipping-related data (parcels, documents, statuses, shipments) into conversational or agent-based workflows.

---

## Pricing

No pricing information is provided in the available content for the Sendcloud MCP Server or its usage via Pipedream. Pricing would need to be obtained from Sendcloud or Pipedream directly.