# Teamgate MCP Server

**Category:** Business & Commerce · MCP Servers  
**Slug:** `teamgate-mcp-server`  
**Source:** https://mcp.pipedream.com/app/teamgate

## Overview
Teamgate MCP Server connects the Teamgate intelligent sales CRM to MCP-compatible AI tools and chat clients. It exposes lead capture, deal management, product catalog, company and contact management, and activity creation capabilities through the MCP protocol using a static server URL.

- **MCP server URL:** `https://mcp.pipedream.net/v2`
- Works with multiple chat / AI clients that support MCP.
- Authentication is handled when adding the server to the client application.

## Features

### CRM & Data Model Coverage
- Integrates with Teamgate, an intelligent sales CRM focused on:
  - Lead capture
  - Deal management from lead to close
  - Reporting and insights
- Supports operations on core CRM entities:
  - Leads
  - Deals
  - Products
  - Companies
  - Persons (contacts)
  - Activities

### MCP Integration
- Static MCP endpoint (`https://mcp.pipedream.net/v2`) usable across all clients.
- Can be added to any compatible chat client or AI tool that supports MCP servers.
- Central configuration handled via Pipedream’s configuration flow.

### Available Tools (Actions)
The server exposes 14 actions as MCP tools:

#### Create operations
- **Create Product**
  - Create a new product in Teamgate.
- **Create Person**
  - Create a new person/contact record.
- **Create Lead**
  - Create a new lead.
- **Create Deal**
  - Create a new deal opportunity.
- **Create Company**
  - Create a new company record.
- **Create Activity**
  - Create a new activity (e.g., task, meeting, call) linked to CRM records.

#### Update operations
- **Update Product**
  - Update an existing product.
- **Update Lead**
  - Update an existing lead.
- **Update Deal**
  - Update an existing deal.
- **Update Cart Products Status**
  - Set all products in a cart as active or inactive.
  - `isActive: true` → product is in stock.
  - `isActive: false` → product is out of stock.

#### Find / Lookup operations
- **Find Product**
  - Look up a product by search parameters.
- **Find Person**
  - Look up a contact/person.
- **Find Lead**
  - Look up a lead.
- **Find Company**
  - Look up a company.

### Usage Context
- Enables AI-powered workflows to:
  - Capture and update leads directly from AI/chat interfaces.
  - Create and manage deals programmatically.
  - Maintain product catalogs and stock status.
  - Manage companies and contacts.
  - Log activities as part of sales workflows.

## Pricing
No specific pricing information for the Teamgate MCP Server is provided in the available content. Pricing may depend on Pipedream and/or Teamgate subscription plans and should be checked on their respective sites.
