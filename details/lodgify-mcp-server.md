# Lodgify MCP Server

**Category:** Business & Commerce – MCP Servers  
**Slug:** `lodgify-mcp-server`  
**Brand:** Lodgify

Lodgify MCP Server exposes Lodgify’s hospitality website and reservation management platform through the Model Context Protocol (MCP), enabling automated handling of bookings and property data from compatible MCP clients.

---

## Features

- **MCP-based access to Lodgify**  
  - Connects MCP-compatible clients to Lodgify’s platform.  
  - Supports integration into chat-based or agent-style applications.

- **Hospitality website management**  
  - Interfaces with Lodgify features for creating and managing hospitality websites.  
  - Designed for sites that include a “Book Now” button for direct online reservations.

- **Reservation and booking handling**  
  - Automates handling of reservations and bookings via Lodgify.  
  - Provides programmatic interaction with booking-related data.

- **Property data access**  
  - Exposes property-related information managed in Lodgify (e.g., listings, availability, and other property data) through MCP tools.

- **Single static MCP endpoint**  
  - Uses one static MCP server URL for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Authentication is performed when the server is added/configured in the client.

- **Client-agnostic integration**  
  - Works with any MCP-capable chat client or application.  
  - Can be added to different agent frameworks that support MCP configuration.

---

## Technical Details

- **Protocol:** Model Context Protocol (MCP)  
- **Server URL:** `https://mcp.pipedream.net/v2` (static for all clients)  
- **Authentication:** Performed during server setup within the client or application.  
- **Hosting / Provider:** Delivered via Pipedream Connect.

---

## Pricing

The provided content does not list any pricing or plan details for Lodgify MCP Server.