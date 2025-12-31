# Wiza MCP Server

## Overview
Wiza MCP Server is an MCP (Model Context Protocol) server that connects MCP-compatible chat clients with Wiza, enabling automated discovery and export of accurate prospect contact data from LinkedIn.

- **Type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Primary Use Case:** Lead generation, sales prospecting, and contact data enrichment from LinkedIn via MCP-compatible clients
- **Provider:** Wiza (via Pipedream Connect)

## Features
- **LinkedIn prospect data access**: Connects your MCP client to Wiza to retrieve prospect contact data sourced from LinkedIn.
- **Accurate contact data export**: Supports exporting accurate prospect contact information for use in sales and lead-generation workflows.
- **Automated discovery**: Enables automated discovery of prospect details instead of manual research on LinkedIn.
- **Static MCP endpoint**: Uses a single static MCP server URL (`https://mcp.pipedream.net/v2`) that works across compatible clients.
- **Client-agnostic integration**: Designed to be added to various MCP-enabled chat clients; the same server URL can be reused.
- **Authentication at setup time**: Authentication is performed when adding the server to an application, keeping the MCP endpoint static.

## Technical Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Integration host:** Pipedream Connect
- **Configuration:** Added to your MCP-compatible chat client using the static URL; further configuration details are available on the provider’s configuration page.

## Pricing
The provided content does not include any pricing information for Wiza MCP Server or Wiza usage. Refer to the provider’s official site or app listing for current pricing details.