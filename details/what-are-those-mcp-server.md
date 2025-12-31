# What Are Those MCP Server

MCP server integration for the “What Are Those” sneaker and fashion recognition service, enabling agents and applications to identify over 1 million sneaker and fashion products with high accuracy.

---

## Overview
- **Type:** MCP server / AI integration
- **Purpose:** Image-based recognition, grading, and lookup of sneakers and fashion products
- **Accuracy:** Up to ~95% recognition accuracy (per service description)
- **Scope:** Over 1M sneaker and fashion products
- **Endpoint:** Static MCP server URL – `https://mcp.pipedream.net/v2`

---

## Features

### MCP Server & Configuration
- Static MCP server URL works for all clients; authentication handled when adding the server to the application.
- Can be added to compatible chat or agent clients as an MCP server.
- Central configuration and account connection via Pipedream:
  - Connect a "What Are Those" account.
  - Select a client and manage connected accounts.
- Configuration documentation available via a full configuration page on Pipedream.

### Available Tools (Actions)

1. **Identify Sneakers from Photo**
   - Input: Uploaded sneaker image.
   - Output details may include:
     - Sneaker name/model.
     - Links (e.g., product or marketplace URLs).
     - Images.
     - Prices.
     - Confidence scores for recognition.
   - Supports identifying sneakers among over 1M products.

2. **Grade and Authenticate Sneakers**
   - Input: Images of sneakers.
   - Functions:
     - Grades sneaker condition.
     - Performs authentication checks.
   - Returns grading and authentication results (specific schema defined in linked docs).

3. **Find Sneakers by SKU**
   - Input: Photo of a size tag / SKU label.
   - Identifies sneakers based on SKU extracted from the tag image.
   - Returns sneaker name and related details.

---

## Use Cases
- Powering AI agents or chatbots that can recognize sneakers and fashion items from photos.
- Enabling automated sneaker authentication and condition grading workflows.
- Building retail, resale, or inventory tools that identify products via photos or SKU tags.

---

## Pricing
Pricing information is not provided in the available content. Refer to the Pipedream or "What Are Those" service pages for current pricing details.