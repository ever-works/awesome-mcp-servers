# Mews MCP Server

Mews MCP Server connects applications to the Mews hospitality management cloud via the Model Context Protocol (MCP), enabling automated workflows around reservations, customers, billing, and hotel operations.

**Category:** Business & Commerce · MCP Servers  
**Tags:** hospitality, reservations, operations

---

## Overview

The Mews MCP Server exposes Mews hospitality management capabilities as MCP tools. Once connected to a Mews account, it can be added to compatible chat or agent clients using a static MCP server URL.

- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Integration:** Connects to a Mews account via Mews Connector APIs
- **Use cases:** Reservation management, customer data management, pricing queries, billing retrieval, and operational tasks (e.g., tasks, orders, products)

---

## Features

### Connection & Configuration
- Static MCP server URL usable across clients, with authentication handled when adding the server to an application.
- Can be added to various chat / agent clients that support MCP.

### Available Tools (Actions)
18 actions are available as tools. The following are documented:

#### Reservations
- **Create Reservation**  
  Create a new reservation in Mews using defined reservation parameters.

- **Update Reservation**  
  Update an existing reservation’s details.

- **Cancel Reservation**  
  Cancel an existing reservation.

- **Fetch Reservations**  
  Retrieve reservations via the Mews Connector API (e.g., for syncing, reporting, or monitoring).

- **Add Reservation Product**  
  Add a product to an existing reservation (e.g., upsells or add-ons).

- **Create Availability Block**  
  Create an availability block in Mews (e.g., for group bookings or inventory holds).

#### Customers / Guests
- **Update Customer**  
  Update an existing customer’s profile and related data.

- **Fetch Customers**  
  Retrieve customers from Mews using the Connector API.

#### Pricing & Products
- **Get Rate Prices**  
  Retrieve rate pricing information for a specific rate and time period.

- **Fetch Products**  
  Retrieve products configured in Mews (e.g., room-related products, services, or add-ons).

- **Add Reservation Product**  
  Attach products to reservations (also listed under Reservations).

#### Orders & Order Items
- **Create Order**  
  Create an order in Mews (e.g., for services or POS-like charges).

- **Fetch Order Items**  
  Retrieve order items via the Mews Connector API.

#### Tasks & Operations
- **Create New Task**  
  Create a new operational task in Mews (e.g., housekeeping or front-desk tasks).

#### Billing
- **Get Bill PDF**  
  Retrieve a bill PDF by bill ID.

#### Other Data
- **Fetch Age Categories**  
  Retrieve all age categories, optionally filtered by service.

> Note: The platform lists 18 total actions; only the actions explicitly shown in the source content are documented above. Additional actions may exist but are not described in the provided content.

---

## Technical Details

- **Protocol:** Model Context Protocol (MCP)
- **Backend:** Uses Mews Connector API for data access and operations
- **Authentication:** Performed when adding the MCP server to a compatible application/client

For implementation specifics of each action (parameters, response formats), refer to the linked GitHub action files in the Mews components directory on the Pipedream repository.

---

## Pricing

No pricing information is provided in the available content. Use of Mews MCP Server may depend on:
- Mews platform subscription or licensing, and
- Any applicable terms from the MCP hosting provider (e.g., Pipedream / Workday), if relevant.

Consult the Mews and platform documentation for current pricing details.