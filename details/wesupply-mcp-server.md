# WeSupply MCP Server

## Overview
The WeSupply MCP Server is an MCP (Model Context Protocol) integration that exposes WeSupply’s post‑purchase customer experience automation capabilities for retail and e‑commerce use cases. It allows applications (such as chat clients and AI agents) to interact with WeSupply features like shipment tracking, delivery predictions, notifications, and returns via a unified MCP endpoint.

- **Category:** Business & Commerce – MCP Servers  
- **Use cases:** Post‑purchase automation, shipment tracking, customer experience workflows, self‑service returns  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Post‑purchase CX automation integration**  
  - Surfaces WeSupply’s post‑purchase features through MCP for use in compatible clients and applications.

- **Pre‑purchase delivery prediction**  
  - Access to WeSupply’s delivery prediction capabilities to estimate delivery windows before purchase (as exposed through WeSupply’s platform via MCP).

- **Automated shipping tracking**  
  - Retrieve and work with shipment status information programmatically through the MCP server.

- **Proactive notifications**  
  - Integrate notification workflows (e.g., shipment updates, status changes) into chat or other MCP‑aware clients.

- **Self‑service returns workflows**  
  - Enable interactions related to returns (e.g., initiating or managing returns) via MCP-connected tools.

- **Static MCP endpoint**  
  - Uses a single static server URL (`https://mcp.pipedream.net/v2`) that works for all clients; authentication is handled when adding the server to a client or application.

- **Multi‑client compatibility**  
  - Designed to be added to different chat clients or applications that support MCP, enabling consistent access to WeSupply tools across environments.

- **Managed via Pipedream**  
  - Hosted and provided through Pipedream’s MCP infrastructure, benefiting from its standard configuration and security model.

## Configuration
- Connect a WeSupply account and select the appropriate client within the Pipedream interface.
- Use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to any supported MCP client or application and authenticate during setup.

## Pricing
The provided content does not include any pricing or plan information for the WeSupply MCP Server.