# Shopify Developer App MCP Server

## Overview
The **Shopify Developer App MCP Server** exposes Shopify’s APIs as Model Context Protocol (MCP) tools, enabling development and automation workflows against a Shopify store from compatible MCP clients (e.g., chat-based or agent applications). It targets the **Shopify Developer App** context and is delivered via Pipedream’s MCP infrastructure.

- **Type:** MCP server / developer integration
- **Category:** business-commerce-mcp-servers
- **Primary use cases:** e‑commerce automation, store management, content updates, inventory and product synchronization, order operations
- **MCP server URL:** `https://mcp.pipedream.net/v2` (static URL used across clients; authentication occurs during client configuration)

## Features

### MCP Server & Configuration
- Static MCP endpoint (`https://mcp.pipedream.net/v2`) usable from any compatible MCP client.
- Authentication handled at the time the server is added to an MCP-compatible application.
- Works in the **Shopify Developer App** context, exposing Shopify APIs as tools/actions.
- Approximately **39 actions available as tools**, covering a wide range of store and content operations.

### Order Management
- **Get Order**
  - Retrieve an order by specifying the order ID.
  - Useful for inspecting order details, status, line items, and performing downstream automations.
- **Refund Order**
  - Initiate an order refund.
  - Can be integrated into automated workflows for returns, cancellations, or support flows.

### Product & Variant Management
- **Update Product Variant**
  - Update an existing product variant.
  - Supports programmatic changes to variant attributes like price, options, or other variant fields (per Shopify’s API and the underlying action implementation).
- **Search for Products**
  - Search for products in a Shopify store.
  - Enables discovery and selection of products for further automated actions (e.g., updates, bundling, or reporting).
- **Search for Product Variant**
  - Search for product variants, with the ability to **create a variant if not found**.
  - Useful for idempotent automations ("find-or-create" patterns) when syncing external catalogs or updating dynamic listings.

### Content & Pages
- **Update Page**
  - Update an existing Shopify page.
  - Suitable for automated content updates, CMS-like workflows, or syncing external content sources.
- **Get Pages**
  - Retrieve a list of all pages.
  - Helps in navigation, content audits, or bulk-update flows.
- **Update Article**
  - Update a blog article.
  - Enables automation and management of blog content, SEO updates, or scheduled posts.

### Metaobjects & Metafields
- **Get Metaobjects**
  - Retrieve a list of metaobjects.
  - Supports advanced content/data modeling use cases in Shopify.
- **Update Metaobject**
  - Update an existing metaobject.
  - Useful for structured data, custom models, and headless-commerce patterns.
- **Get Metafields**
  - Retrieve a list of metafields that belong to a given resource.
  - Supports reading extended metadata for products, variants, orders, or other resources.
- **Update Metafield**
  - Update a metafield belonging to a resource.
  - Allows automation of metadata changes (e.g., flags, tags, configuration values, or integration keys).

### Inventory Management
- **Update Inventory Level**
  - Set the inventory level for an inventory item at a location.
  - Enables real-time or scheduled inventory synchronization, multi-location adjustments, and stock automation.

### Collections & Search
- **Search Custom Collection by Name**
  - Search for a custom collection by its name/title.
  - Useful for associating products or content with specific collections in automated flows.

### Tooling Scope
- Total of **39 actions** (tools) are available for use via MCP, beyond the explicitly listed examples above. These cover a broad range of Shopify API capabilities across products, orders, content, and store configuration.

## Pricing
Pricing information is **not provided** in the available content. Use the main Pipedream or Shopify Developer App documentation/pricing pages to determine any associated costs for this MCP server or its underlying platform usage.
