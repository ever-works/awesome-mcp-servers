# Donately MCP Server

## Overview
Donately MCP Server is an MCP (Model Context Protocol) integration that connects Donately’s online donation platform to MCP-compatible clients. It enables tools and agents to help manage and automate online donation collection, donor data, and fundraising workflows through a unified MCP endpoint.

- **Category:** Business & Commerce – MCP Servers  
- **Use cases:** Fundraising, donations, nonprofit workflows
- **MCP server URL:** `https://mcp.pipedream.net/v2` (static for all clients; authentication handled when adding the server to your app)

## Features
Based on the available information (and the Donately platform focus), the MCP server is intended to expose Donately capabilities into MCP-compatible tools, including:

- **Online donation collection integration**  
  - Connects to Donately’s online donation platform so MCP clients can help manage donation flows.

- **Support for organizations of various sizes**  
  - Designed for use by small to large organizations that collect donations online (e.g., nonprofits, fundraising teams, campaigns).

- **Central MCP endpoint**  
  - Uses a single static URL (`https://mcp.pipedream.net/v2`) for all clients, simplifying configuration across different MCP-enabled apps and chat clients.

- **Client-agnostic setup**  
  - Same server URL for any supported chat client or MCP application; authentication is performed when the server is added to the client.

- **Configuration documentation available**  
  - Detailed setup and configuration steps are provided via the linked Configuration page (outside this summary), covering how to add the server to various clients.

> Note: The provided content does not list individual API methods or detailed capabilities (e.g., specific donor or campaign endpoints). The bullet points above reflect the scope explicitly described: integrating Donately’s online donation platform via MCP with a static, client-agnostic server URL.

## Pricing
No pricing information is provided in the supplied content for either the Donately MCP Server or the underlying Donately service. Pricing details would need to be obtained directly from Donately or Pipedream’s documentation or pricing pages.