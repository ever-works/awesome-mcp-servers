# Amazon Selling Partner MCP Server

Amazon Selling Partner MCP Server is an MCP integration for the Amazon Selling Partner API (SP-API), enabling MCP-aware agents to programmatically access Amazon seller data, including orders, shipments, payments, and more, to support automation and business workflows.

---

## Overview

- **Type:** MCP Server / Integration
- **Category:** Business & Commerce – MCP Servers
- **Brand:** Amazon
- **Source URL:** https://mcp.pipedream.com/app/amazon_selling_partner
- **MCP Server Base URL:** `https://mcp.pipedream.net/v2`

This server exposes the Amazon Selling Partner API (SP-API) to MCP-aware applications, allowing them to interact with Amazon seller account data in a structured, programmatic way.

---

## Features

- **Programmatic Access to Seller Data**  
  - Access orders, shipments, payments, and other Amazon seller data via SP-API.  
  - Designed for MCP-aware agents and applications.

- **Support for Key SP-API Domains**  
  While the underlying SP-API covers many domains, this MCP server is described as providing access to:  
  - **Orders**: Retrieve information about customer orders.  
  - **Shipments**: Access shipment-related data for fulfillment and logistics workflows.  
  - **Payments**: Access payment-related information for reconciliation and financial workflows.  
  - **“And much more” seller data** (i.e., additional SP-API resources as exposed by the integration).

- **Automation & Workflow Integration**  
  - Intended to help automate seller operations with MCP-aware agents (e.g., AI assistants, tools, or orchestrators).  
  - Can be used to improve operational efficiency and reduce manual work around orders, shipping, and payment management.

- **Single Static MCP Endpoint**  
  - Uses a static MCP server URL that works across compatible clients:  
    - `https://mcp.pipedream.net/v2`  
  - Authentication is performed when adding the server to the client or application.

- **Client-Agnostic Integration**  
  - Designed to be added to multiple MCP-compatible chat or agent clients.  
  - Configuration details are available via the linked configuration documentation (on the source site).

---

## Authentication & Configuration

- **Static Server URL:** `https://mcp.pipedream.net/v2`  
- **Authentication:** Performed when adding the server to your MCP-aware client or application (specific auth steps are defined in the client/configuration documentation, not in the provided text).  
- **Configuration:** Additional setup and configuration instructions are provided on the external configuration page linked from the source.

---

## Pricing

No pricing information is provided in the supplied content. Use the source URL or provider site to check for any usage or subscription details.
