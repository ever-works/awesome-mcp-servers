# Veriphone MCP Server

An MCP server integration for Veriphone that provides phone number validation and carrier lookup through MCP-compatible tools.

## Overview
- **Type:** MCP server integration
- **Category:** Security & attestation MCP servers
- **Provider / Brand:** Veriphone (via Pipedream Connect)
- **Slug:** `veriphone-mcp-server`
- **MCP Server Base URL:** `https://mcp.pipedream.net/v2`

## Features
- **Phone Number Validation**
  - Validate phone numbers through Veriphone’s API via an MCP-compatible interface.
  - Useful for checking whether a given phone number is correctly formatted and valid.

- **Carrier Lookup**
  - Retrieve carrier information associated with a phone number using Veriphone data.
  - Can be integrated into workflows that require telecom or routing metadata.

- **MCP-Compatible Integration**
  - Exposed as an MCP server so it can be added to MCP-capable chat clients and tools.
  - Uses a static MCP server URL (`https://mcp.pipedream.net/v2`) that works across clients, with authentication handled when you add the server to your application.

- **Pipedream Connect Integration**
  - Hosted and powered by Pipedream Connect.
  - Centralized configuration via a Pipedream configuration page (for setup and management in supported clients).

## Configuration
- **Server URL:**
  - Use `https://mcp.pipedream.net/v2` as the MCP server endpoint in your MCP-compatible client.
- **Client Setup:**
  - Add the MCP server URL in your chat or MCP client.
  - Authenticate within your application/client during setup (specific auth steps depend on the client and are handled at integration time).
- **Documentation:**
  - Additional configuration details are available on the referenced configuration page in the Pipedream Connect environment.

## Pricing
- Not specified in the provided content.