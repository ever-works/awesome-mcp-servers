# Infobip MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Pipedream  
**Slug:** `infobip-mcp-server`

## Description
Infobip MCP Server is an MCP (Model Context Protocol) server integration on Pipedream that exposes Infobip’s multi-channel communications platform to compatible clients and workflows. It enables interaction with Infobip channels such as SMS and chat through a standardized MCP endpoint.

## Key Details
- **Platform:** Pipedream (Pipedream Connect)
- **Service Type:** MCP server integration for Infobip
- **Primary Use Cases:** Multi-channel messaging, notifications, and chat-based communications via Infobip within MCP-compatible applications and workflows
- **MCP Server Base URL:** `https://mcp.pipedream.net/v2` (static URL for all clients; authentication is applied when adding the server)

## Features
- **Multi-channel messaging via Infobip**  
  - Access to Infobip’s multi-channel communications platform (e.g., SMS, chat, and other supported Infobip channels) through MCP.

- **Standard MCP server endpoint**  
  - Single static MCP server URL: `https://mcp.pipedream.net/v2` used across clients.
  - Authentication is performed when the server is added to a client or application.

- **Client-agnostic integration**  
  - Designed to be added to different MCP-compatible chat clients or applications.  
  - Works as a shared MCP server endpoint; configuration is handled per client.

- **Configuration documentation**  
  - Detailed setup and configuration steps are available via the Pipedream Configuration page (linked from the product page).

## Integration & Usage
- Add the MCP server to your preferred MCP-compatible chat client or application using:  
  `https://mcp.pipedream.net/v2`
- Authenticate during setup within the client/application according to its MCP server configuration flow.
- Use the integration in Pipedream-based or MCP-compatible workflows to send or manage Infobip-powered communications.

## Pricing
No pricing information is provided in the available content. Users should refer to Pipedream and Infobip pricing pages for details on any associated costs.