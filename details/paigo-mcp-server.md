# Paigo MCP Server

## Overview
The Paigo MCP Server is an MCP-based integration that lets AI and MCP-compatible tools interact with Paigo’s SaaS billing automation and subscription management platform. It connects to a Paigo account via a static MCP server URL and exposes billing and subscription operations as tools.

- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Provider / Brand:** Paigo (via Pipedream)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration & Configuration
- Static MCP server URL used for all clients; authentication handled when adding the server to the application.
- Designed to be added to compatible chat or AI client applications as an MCP server.
- Works with Paigo accounts to manage SaaS billing and subscriptions programmatically.

### Available Tools (Actions)
The MCP server exposes 6 actions as tools:

1. **Onboard Customer**
   - Creates a new customer in Paigo.
   - Assigns the new customer to a specific offering.

2. **Measure Usage**
   - Records usage data for a specific usage type.
   - Links recorded usage to a specific customer.

3. **Get Invoice**
   - Retrieves detailed information about a specific invoice in Paigo.

4. **Create Offering**
   - Creates a new offering in the Paigo platform.
   - Supports defining products/plans to assign to customers.

5. **Create Dimension**
   - Creates a new dimension in Paigo.
   - Used for structuring or categorizing billing/usage data.

6. **Add Credits**
   - Increments the credit balance of a specified customer.
   - Supports credit-based billing or prepaid balances.

## Use Cases
- Automating customer onboarding into Paigo from AI assistants or chat-based workflows.
- Recording metered usage events for customers programmatically via MCP tools.
- Fetching invoice details for display, analysis, or customer support workflows.
- Managing offerings, billing dimensions, and customer credit balances from within MCP-compatible applications.

## Pricing
No pricing information is provided in the available content for the Paigo MCP Server.