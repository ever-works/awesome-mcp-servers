# Chaser MCP Server

An MCP (Model Context Protocol) server for integrating Chaser’s credit control and collections workflows into AI tools and chat-based applications.

**Website:** https://mcp.pipedream.com/app/chaser  
**MCP Server URL:** `https://mcp.pipedream.net/v2`

## Overview
The Chaser MCP Server, powered by Pipedream Connect, exposes Chaser’s credit control and collections capabilities to AI workflows. It enables applications to manage credit checks, monitor debtors, chase invoices, and handle collections directly from an MCP-compatible client.

## Features
- **Credit Checks**
  - Run or trigger credit checks on customers or debtors from within AI workflows.

- **Debtor Monitoring**
  - Monitor debtor status and behavior to support proactive credit control.

- **Invoice Chasing**
  - Automate chasing of unpaid invoices.
  - Support for sending outbound messages by:
    - Email
    - Text (SMS)

- **Collections Management**
  - Manage and coordinate collection activities for overdue invoices.
  - Support workflows from initial reminders through to debt recovery.

- **Unified Workflow Integration**
  - Access all credit-control related actions (credit checks, monitoring, chasing, and collections) in one place through a single MCP server endpoint.
  - Designed to be added once (`https://mcp.pipedream.net/v2`) and then authenticated per client/app.

- **MCP/Chat Client Compatibility**
  - Can be added to MCP-compatible chat clients and AI assistants.
  - Central configuration via a static MCP server URL; authentication handled when adding the server to the application.

## Setup / Integration
- Use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-compatible app or chat client, then authenticate as prompted.
- Additional configuration details are available on the associated configuration page (via Pipedream Connect).

## Category
- Business & Commerce MCP Servers

## Tags
- Invoicing  
- Collections  
- Accounting

## Pricing
Pricing information is not provided in the available content. Users should refer to the primary Chaser or Pipedream/Workday sites for current pricing and plan details.