# Shipengine MCP Server

**Brand:** Pipedream  
**Category:** Business & Commerce – MCP Servers  
**Slug:** `shipengine-mcp-server`  
**Source:** https://mcp.pipedream.com/app/shipengine

Shipengine MCP Server is a Pipedream-hosted MCP integration that exposes Shipengine’s multi-carrier shipping API and logistics capabilities to MCP-compatible clients and LLM agents.

---

## Features

### MCP Server & Connectivity
- Pipedream-hosted MCP server for Shipengine’s shipping and logistics API.
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
- Works with multiple MCP-compatible chat clients and LLM agents.
- Authentication handled when adding the server to your application.

### Account & Configuration
- Connect and manage Shipengine accounts via Pipedream.
- Configure Shipengine once and reuse across supported MCP clients.
- Central configuration reference via the Pipedream Configuration page.

### Available Tools (Actions)

1. **Validate An Address**
   - Validates shipping addresses via Shipengine.
   - Helps ensure accurate addresses before shipping.
   - Can reduce issues related to invalid or incomplete addresses.

2. **Start Tracking a Package**
   - Subscribes to tracking updates for a shipment.
   - Enables automated retrieval of tracking events via MCP tools.

3. **Search Labels**
   - Returns shipping labels, 25 at a time, starting with the most recently created.
   - Supports multiple filter options to narrow results (e.g., by status or other criteria as exposed by Shipengine’s label search API).

4. **Find Tracking Status**
   - Retrieves package tracking information for a shipment.
   - Provides current tracking status via Shipengine’s tracking API.

---

## Integration Context
- Designed for commerce and logistics workflows (shipping, label management, tracking).
- Exposes Shipengine’s multi-carrier shipping system to tools and agents operating over MCP.

---

## Pricing
- No pricing information is provided in the available content.