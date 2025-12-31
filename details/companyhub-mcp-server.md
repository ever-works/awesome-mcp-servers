# CompanyHub MCP Server

CompanyHub MCP Server is an MCP (Model Context Protocol) server integration that lets tools read and manipulate sales-automation CRM data from CompanyHub, a customizable CRM for sales teams across different industries.

---

## Overview
- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Purpose:** Enable AI/chat clients and MCP tools to interact with CompanyHub CRM data, focusing on core sales objects such as deals, contacts, and companies.
- **Provider:** Pipedream (powered by Pipedream Connect)

---

## Connection & Configuration
- **Static MCP Server URL:** `https://mcp.pipedream.net/v2`
  - Same URL for all clients; authentication is handled when adding the server to your application.
- **Authentication:** Sign in via Pipedream to connect your CompanyHub account.
- **Client Setup:**
  - Can be added to compatible chat clients (e.g., ChatGPT / OpenAI) as an MCP server.
  - Additional setup details available on the Pipedream MCP Configuration page.

---

## Features

### Core Capabilities
- Connect a CompanyHub CRM account to MCP-compatible applications.
- Allow tools/agents to perform write operations on key CRM entities.
- Provide a standardized MCP endpoint to integrate sales-automation workflows into chat-based or automated systems.

### Available Tools (Actions)
The server currently exposes three primary actions as tools:

1. **Create Deal**
   - Creates a new deal record in CompanyHub.
   - Intended for automating deal creation from conversations, workflows, or other MCP-aware applications.

2. **Create Contact**
   - Creates a new contact in CompanyHub.
   - Useful for capturing leads or people records directly from chat or automation flows.

3. **Create Company**
   - Creates a new company record in CompanyHub.
   - Supports maintaining and expanding the company account list programmatically.

---

## Pricing
No pricing information is provided in the available content. Usage may depend on:
- Your Pipedream account and plan.
- Your CompanyHub subscription.

Refer to Pipedream and CompanyHub directly for current pricing and plan details.