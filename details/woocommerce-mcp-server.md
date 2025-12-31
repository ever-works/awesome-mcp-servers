# WooCommerce MCP Server

## Overview
WooCommerce MCP Server is an MCP (Model Context Protocol) server integration that connects to WooCommerce, the open‑source ecommerce platform for WordPress. It exposes store data such as products, orders, customers, and order notes as tools that can be invoked from compatible MCP clients.

- **Type:** MCP server integration
- **Platform:** WooCommerce (WordPress ecommerce)
- **Provider:** Pipedream
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### General
- Integrates a WooCommerce store with MCP-compatible applications.
- Uses a single static MCP server URL for all clients.
- Authentication occurs when adding the server to an application.
- Supports configuring and connecting a WooCommerce account for use in chat or other MCP-enabled clients.

### Available Tools (Actions)
The WooCommerce MCP Server exposes 16 actions as tools:

#### Products
- **Create Product** – Create a new product in WooCommerce.
- **Update Product** – Update an existing product.
- **Get Product** – Retrieve a specific product by identifier.
- **List Products** – Retrieve a list of products.

#### Orders
- **Create Order** – Create a new order.
- **Get Order** – Retrieve a specific order.
- **List Orders** – Retrieve a list of orders.
- **Update Order Status** – Update the status of a specific order.
- **Delete Order** – Delete an existing order.

#### Order Notes
- **Add Order Note** – Create a new note for an order.
- **Get Order Note** – Retrieve a specific order note.
- **List Order Notes** – Retrieve a list of notes for a specific order.

#### Customers
- **Create Customer** – Create a new customer.
- **Get Customer** – Retrieve a specific customer.
- **Search Customers** – Find customers by search criteria.

#### Refunds
- **Create Refund** – Create a new refund for an order.

## Configuration
- Connect a WooCommerce account via the Pipedream interface.
- Use the static MCP server URL `https://mcp.pipedream.net/v2` when adding the server to an MCP-compatible app.
- Configuration guides are available per client type and via the general configuration page on Pipedream.

## Pricing
Pricing details for the WooCommerce MCP Server are not provided in the given content. Use of this integration is subject to Pipedream’s general Terms and Privacy Policy.