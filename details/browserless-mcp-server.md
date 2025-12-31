# Browserless MCP Server

**Category:** Code Execution & Automation MCP Servers  
**Brand:** browserless  
**Source:** https://mcp.pipedream.com/app/browserless

## Description
Browserless MCP Server is an MCP server integration that provides MCP-compatible clients with access to headless Chrome instances in the cloud via Browserless. It enables automated web browsing, scraping, and testing workflows through a standardized MCP endpoint.

## Features
- **Headless Chrome in the cloud**
  - Run Chrome instances remotely without managing your own infrastructure.
  - Suitable for automation, scraping, and browser-based testing.

- **MCP server integration**
  - Exposes Browserless capabilities as an MCP-compliant server.
  - Allows any MCP client to connect through a consistent interface.

- **Static MCP server URL**
  - Single shared endpoint for all clients:  
    `https://mcp.pipedream.net/v2`
  - Same URL works across different MCP-compatible applications.

- **Authentication at client configuration**
  - Authentication is performed when adding the server to your application.
  - Supports secure access control on top of the shared URL.

- **Client-agnostic setup**
  - Can be added to various MCP-enabled chat or automation clients.
  - Configuration guidance available via the referenced configuration page.

- **Use cases**
  - Browser automation (navigation, form filling, interactions).
  - Web scraping and data extraction from websites.
  - Automated UI and end-to-end testing using headless Chrome.

## Integration Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Provider:** Pipedream Connect (hosting the MCP endpoint for Browserless)
- **Access model:** Add the server URL to your MCP-compatible client and authenticate during setup.

## Pricing
The provided content does not include any pricing or plan details for the Browserless MCP Server or Browserless itself.