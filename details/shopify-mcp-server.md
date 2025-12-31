### Shopify MCP Server

**Description**  
An MCP (Model Context Protocol) server that integrates with Shopify’s commerce platform. It exposes Shopify operations as tools/actions so MCP-compatible clients can interact with a Shopify store to manage products, orders, pages, inventory, metafields, and more via OAuth authentication.

**Source**  
https://mcp.pipedream.com/app/shopify

**Category**  
Business & Commerce · MCP Servers

**Tags**  
shopify, e-commerce, online-store

---

### Features

**MCP Server & Connectivity**
- OAuth-based connection to a Shopify store.
- Single static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
- Can be added to any compatible chat or MCP client via the server URL.
- Uses Shopify’s APIs to perform commerce operations as MCP tools.

**Available Tools / Actions**  
(39 total actions available; the following are the ones explicitly listed in the provided content.)

**Product & Variant Management**
- **Update Product**: Update an existing product’s details.
- **Update Product Variant**: Update an existing product variant’s attributes.
- **Search for Products**: Search for products in the store.
- **Search for Product Variant**: Search for product variants and optionally create a variant if not found.

**Order Management**
- **Update Order**: Update an existing order.
- **Search for Orders**: Search for a single order or a list of orders.

**Content & Pages**
- **Update Page**: Update an existing store page.
- **Get Pages**: Retrieve a list of all pages.
- **Update Article**: Update a blog article.

**Metaobjects & Metafields**
- **Update Metaobject**: Update an existing metaobject.
- **Get Metaobjects**: Retrieve a list of metaobjects.
- **Update Metafield**: Update a metafield that belongs to a resource.
- **Get Metafields**: Retrieve a list of metafields belonging to a resource.

**Inventory Management**
- **Update Inventory Level**: Set the inventory level for an inventory item at a specific location.

**General Notes**
- Total of 39 Shopify actions are available as MCP tools, enabling broad coverage of store operations (products, orders, customers, content, inventory, custom data, etc.), though only a subset is listed explicitly in the provided content.

---

### Configuration
- Connect via Shopify OAuth to authorize access to your store.
- Use the static MCP server URL `https://mcp.pipedream.net/v2` when adding the server to a client.
- Client-specific setup instructions are available via the "Add the server to your app" workflow and configuration documentation (not reproduced here).

---

### Pricing
- Not specified in the provided content.