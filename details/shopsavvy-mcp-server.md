# ShopSavvy MCP Server

## Overview
ShopSavvy MCP Server is a Model Context Protocol (MCP) server that integrates with the ShopSavvy Data API to provide AI assistants with product lookup, pricing, and historical pricing data. It enables product search via barcode, ASIN, or URL and exposes rich product metadata and price history for commerce-related use cases.

- **Category:** Business & Commerce MCP Servers  
- **License:** MIT  
- **Source:** https://github.com/shopsavvy/shopsavvy-mcp-server

## Features
- **MCP integration**  
  - Implements a Model Context Protocol (MCP) server for use with AI assistants and compatible clients.

- **Product lookup & search**  
  - Product search by barcode.  
  - Product search by ASIN.  
  - Product search by URL.  
  - Access to ShopSavvy’s product catalog via the ShopSavvy Data API.

- **Pricing data**  
  - Current pricing information for products.  
  - Price comparison capabilities using ShopSavvy’s pricing data.

- **Historical data**  
  - Access to historical price data (price history tracking).  
  - Enables analysis of price changes over time.

- **Rich product metadata**  
  - Retrieval of detailed product information (metadata) from ShopSavvy (e.g., identifiers, descriptive attributes, and other structured data exposed by the API).

- **Developer-focused repository**  
  - Example configurations in the `examples` directory.  
  - TypeScript/Bun project setup (with `src`, `package.json`, `tsconfig.json`, and `bun.lock`).  
  - Contribution guidelines via `CONTRIBUTING.md`.

## Pricing
No pricing information is provided in the repository content. The MCP server itself is open source under the MIT license; any costs related to using the underlying ShopSavvy Data API are not specified here.