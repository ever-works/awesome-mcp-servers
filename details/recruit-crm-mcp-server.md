# Recruit CRM MCP Server

Recruit CRM MCP Server is an MCP Server integration that exposes Recruit CRM’s recruitment and staffing CRM/ATS functionality via the Model Context Protocol (MCP).

## Overview
- **Type:** MCP Server integration
- **Category:** Business & Commerce – MCP Servers
- **Provider / Brand:** Recruit CRM (via Pipedream Connect)
- **Use Case:** Programmatic and chat-based access to a recruitment and staffing CRM / ATS
- **Industries:** Recruitment agencies, staffing firms, talent acquisition teams

## Features
- **MCP-based access to Recruit CRM**  
  - Connects Recruit CRM to MCP-compatible chat clients and tools.  
  - Enables interaction with recruitment and staffing CRM / ATS data through MCP.

- **Static MCP server endpoint**  
  - Single, shared server URL for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Authentication is handled when adding the server to your MCP-compatible application.

- **Client-agnostic integration**  
  - Designed to work with multiple MCP-enabled chat clients.  
  - Setup instructions are available per client through the configuration documentation.

- **Cloud-based infrastructure**  
  - Built on Pipedream Connect’s infrastructure.  
  - Provides a hosted MCP server; no need to run your own server for Recruit CRM access.

- **Configuration documentation**  
  - Central configuration guide available through the “Configuration” page for details on adding the server to supported clients.

## Integration & Usage
- Add the MCP server URL `https://mcp.pipedream.net/v2` to your MCP-compatible chat client.  
- Authenticate with your Recruit CRM / Pipedream account during setup.  
- Once connected, your client can call Recruit CRM functionality over MCP (exact tools and schemas depend on the server’s MCP implementation).

## Pricing
- Not specified in the provided content.

## Additional Information
- **Source / App page:** https://mcp.pipedream.com/app/recruit_crm
- **Platform:** Powered by Pipedream Connect.
- **Policies:** Terms and Privacy Policy are provided by Pipedream (links available on the app page).