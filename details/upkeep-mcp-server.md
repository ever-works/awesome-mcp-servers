# UpKeep MCP Server

**Category:** Business & Commerce – MCP Servers  
**Integration Type:** MCP server for UpKeep (via Pipedream)

MCP server integration that exposes core UpKeep maintenance and asset management operations as tools for MCP-compatible agents. Enables agents and chat-based clients to interact with UpKeep’s CMMS (computerized maintenance management system) for work orders, requests, assets, locations, vendors, and purchase orders.

---

## Features

### MCP Server & Configuration
- **Static MCP server URL:** `https://mcp.pipedream.net/v2` (shared across clients; authentication handled when adding the server to the application).
- **Usable with multiple MCP-compatible chat clients:** configuration guides available per client via the Pipedream configuration page.
- **Account connection:** sign in with UpKeep through Pipedream to connect and manage UpKeep accounts from MCP clients.

### Available Tools (Actions)
The server exposes 9 UpKeep actions as tools:

#### Purchasing & Vendors
- **Create Purchase Order**  
  - Create new purchase orders in UpKeep via MCP.  
  - Accessible as a dedicated MCP tool.

- **Update Purchase Order**  
  - Update existing purchase orders (e.g., status or details) through the MCP interface.

- **Find Vendor**  
  - Search for vendors based on configured properties.  
  - If no filters/props are provided, returns all vendors.  
  - Note: limited to UpKeep enterprise/business-plus plans.

#### Work Management
- **Create Work Order**  
  - Create new work orders in UpKeep via MCP agents or chat clients.

- **Create Request**  
  - Create new maintenance/ service requests in UpKeep through MCP.

#### Asset & Inventory Data
- **Find Asset**  
  - Search for assets by specific properties.  
  - Returns matching assets; if no filters are set, returns all assets.

- **Find Part**  
  - Search for parts (inventory items) based on configured properties.  
  - If no filters are provided, returns all parts.

#### Locations & Users
- **Find Location**  
  - Look up locations with optional filtering by properties.  
  - Returns all locations when no filters are set.

- **Find User**  
  - Search for users by selected properties.  
  - Returns all users if no filters are specified.

---

## Technical Details
- **Host / Provider:** Pipedream MCP infrastructure.  
- **Authentication:** Performed when adding the MCP server to the client; the URL itself is static.  
- **Docs:** Each tool has a corresponding implementation and usage documentation in the Pipedream GitHub repository (linked from the Pipedream UI for this integration).

---

## Pricing
No explicit pricing information for the MCP server itself is provided in the source content.  
Note: the **Find Vendor** action is restricted to UpKeep **enterprise / business-plus** plans, indicating that access to some tools depends on the underlying UpKeep subscription tier.