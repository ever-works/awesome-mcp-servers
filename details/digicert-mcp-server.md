# DigiCert MCP Server

**Category:** Security / Attestation MCP Servers  
**Brand:** DigiCert

## Overview
DigiCert MCP Server is an MCP (Model Context Protocol) server integration that exposes DigiCert’s digital certificate and PKI (Public Key Infrastructure) capabilities to MCP-compatible clients. It enables applications to interact with DigiCert-related certificate management workflows through a standardized MCP endpoint.

- **MCP endpoint URL:** `https://mcp.pipedream.net/v2`
- **Integration host:** Pipedream Connect

## Features
Based on the available information, this integration provides:

- **MCP-accessible DigiCert operations**  
  - Integrates DigiCert’s digital certificate and PKI services into any MCP-compatible client.
  - Uses a single static MCP server URL that can be reused across different clients.

- **Standardized MCP server endpoint**  
  - A fixed MCP endpoint (`https://mcp.pipedream.net/v2`) for connecting tools and applications.  
  - Authentication is handled at the time the server is added to the application.

- **Client-agnostic configuration**  
  - Designed to work with multiple chat or MCP-enabled clients.  
  - Configuration guidance available via a central configuration page (not specific to a single client).

> Note: The source content does not list specific certificate lifecycle operations (e.g., issue, renew, revoke) or detailed PKI workflows, only that the integration exposes DigiCert’s digital certificate and PKI services through MCP.

## Usage
- Add the MCP server URL `https://mcp.pipedream.net/v2` to your MCP-capable or chat-based application.  
- Authenticate within your client when prompted to enable DigiCert-related functionality.

## Pricing
The provided content does not include any pricing or plan information for the DigiCert MCP Server integration.