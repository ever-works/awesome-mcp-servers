# Etsy MCP Server

**Category:** Business & Commerce · MCP Servers  
**Brand:** Etsy  
**Source:** https://mcp.pipedream.com/app/etsy

An MCP-compatible server that connects agents and applications to Etsy, enabling search and interaction with data for handmade, vintage, and custom goods listings.

---

## Features

### MCP Server & Connection
- MCP-compatible server for integrating Etsy data into chat clients or MCP-enabled applications.
- Single static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
- OAuth-based authentication when adding the server to applications.
- Usable across multiple chat clients; configuration guidance available per client.

### Listing Management Tools (Actions)
The server exposes 6 Etsy actions as tools:

1. **Update Listing Property**
   - Updates or populates the properties list defining product offerings for a listing.
   - Supports specifying `value` and `value_id` for each offering.
   - Validates `value` / `value_id` against a `scale_id` already assigned to the listing, or allows assigning a `scale_id` in the same request.

2. **Update Listing Inventory**
   - Updates inventory for a listing identified by its listing ID.
   - Designed for synchronizing stock levels and inventory attributes for a specific listing.

3. **Get Listing**
   - Retrieves a listing record by listing ID.
   - Provides programmatic access to listing details for use in agents or automations.

4. **Get Listing Inventory**
   - Retrieves the inventory record for a listing by listing ID.
   - Useful for reading current stock and inventory configuration before updates.

5. **Delete Listing**
   - Uses an Etsy Open API v3 endpoint to delete a `ShopListing`.
   - Supports deletion only when the listing state is one of:
     - `SOLD_OUT`, `DRAFT`, `EXPIRED`, `INACTIVE`, `ACTIVE` and `is_available`, or
     - `ACTIVE` with one of the seller flags: `SUPRESSED` (frozen), `VACATION`, `CUSTOM_SHOPS` (pattern), `SELL_ON_FACEBOOK`.

6. **Create Draft Listing Product**
   - Creates a **physical** draft listing product in a shop on the Etsy channel.
   - Intended for preparing new listings before they go live.

---

## Technical Details
- Protocol: MCP server (Model Context Protocol) exposing Etsy actions as tools.
- Endpoint: `https://mcp.pipedream.net/v2` (static for all clients).
- Requires user sign-in to connect and manage Etsy accounts.

---

## Pricing
No pricing information is provided in the available content.