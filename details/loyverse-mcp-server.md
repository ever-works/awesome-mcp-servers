# Loyverse MCP Server

## Overview
Loyverse MCP Server provides Model Context Protocol (MCP) access to Loyverse’s point-of-sale (POS) and inventory management capabilities for small and medium businesses. It is delivered via Pipedream and is intended to enable AI-driven workflows that interact with retail sales, stock levels, and reporting data.

- **Category:** Business & Commerce – MCP Servers
- **Brand:** Loyverse
- **Deployment URL (MCP endpoint):** `https://mcp.pipedream.net/v2`

## Features
- **MCP-based access to Loyverse:**
  - Exposes Loyverse POS and inventory functionality through the Model Context Protocol for integration with AI agents and chat clients.
- **Retail sales workflows (via Loyverse POS):**
  - Access to Loyverse’s point-of-sale features for use in AI workflows around retail sales (e.g., querying sales data, building sales-related automations).  
- **Inventory management workflows:**
  - Integration with Loyverse’s inventory management capabilities to support workflows involving stock levels and related inventory data.
- **Reporting-oriented workflows:**
  - Designed to enable AI flows that reference or act on reporting information derived from Loyverse POS and inventory data.
- **Static MCP server URL:**
  - Single, static base URL (`https://mcp.pipedream.net/v2`) used for all clients; authentication occurs when adding the server to an application.
- **Multi-client integration:**
  - Can be added to various chat or AI clients that support MCP; configuration is guided per client from the Pipedream interface.
- **Account-based configuration:**
  - Connect a Loyverse account within Pipedream, then select the appropriate client and use the MCP server URL for integration.

## Configuration & Usage
- Connect your Loyverse account in the Pipedream Loyverse MCP Server page.
- Copy the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your compatible MCP chat client or application.
- Authentication is handled when the server is added to the app.

## Pricing
The provided content does not include any pricing information for the Loyverse MCP Server on Pipedream.