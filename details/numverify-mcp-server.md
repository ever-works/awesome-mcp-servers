# numverify MCP Server

Global phone number validation & lookup JSON API server compatible with the Model Context Protocol (MCP).

- **Name:** numverify MCP Server  
- **Brand:** numverify  
- **Category:** Security & Attestation MCP Servers  
- **Slug:** `numverify-mcp-server`  
- **Source URL:** https://mcp.pipedream.com/app/numverify

## Description
numverify MCP Server exposes the numverify phone number validation and lookup JSON API as an MCP-compatible server. It enables automated validation and lookup of global phone numbers within MCP-enabled applications and workflows.

## Features
- **MCP-compatible server**  
  - Implements an MCP server interface for use with MCP-aware chat clients and tools.
- **Global phone number validation**  
  - Validates phone numbers from multiple countries and formats.  
  - Ensures numbers conform to expected structure for global telephony.
- **Phone number lookup**  
  - Provides lookup details for phone numbers via numverify’s JSON API (e.g., metadata about the number where supported by numverify).
- **JSON API integration**  
  - Wraps the numverify JSON API, exposing its functionality over MCP.
- **Static MCP server URL**  
  - Single endpoint for all clients: `https://mcp.pipedream.net/v2`.  
  - Same URL can be reused across different chat clients and applications.
- **Authentication at client configuration**  
  - Authentication is performed when adding the server to your application or chat client (exact mechanism depends on the client and configuration).  
- **Works with multiple chat clients**  
  - Designed to be added as a server to various MCP-enabled chat applications.  
- **Configuration documentation**  
  - Detailed setup and configuration instructions available via the external Configuration page linked from the product page.

## Integration & Usage
- **Server URL:** `https://mcp.pipedream.net/v2`  
- **Usage pattern:**  
  1. Add the MCP server URL to an MCP-compatible client or app.  
  2. Authenticate during server setup in the client.  
  3. Use provided tools or commands (in the client) to validate and look up phone numbers via numverify.

## Pricing
The provided content does not list any pricing or plan information for numverify MCP Server.