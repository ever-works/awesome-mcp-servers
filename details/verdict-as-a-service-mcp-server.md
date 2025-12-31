# Verdict as a Service MCP Server

## Overview
Verdict as a Service MCP Server is an MCP-compatible security scanning service that lets applications scan files for malware and other threats via a simple, easily integrated API endpoint.

- **Category:** Security & Attestation MCP Servers
- **Provider / Brand:** Verdict-as-a-Service (via Pipedream)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Malware and Threat Scanning**  
  - Scans files for malware and other security threats.  
  - Designed for automated, programmatic scanning within applications.

- **MCP-Compatible Server**  
  - Exposed as an MCP server endpoint that can be added to MCP-enabled environments and chat clients.  
  - Uses a static server URL (`https://mcp.pipedream.net/v2`) for all clients.

- **Application Integration**  
  - Intended for easy integration with minimal code changes.  
  - Functions as a security scanning API that applications can call to submit files / objects for analysis.

- **Account-Based Access**  
  - Requires connecting a Verdict-as-a-Service / Pipedream account before use.  
  - Authentication occurs when adding the server to the application or client.

## Configuration
- Connect your account in Pipedream to enable the Verdict-as-a-Service MCP Server.  
- Use the static MCP server URL: `https://mcp.pipedream.net/v2`.  
- Add the server to your chat client or application following the relevant client instructions (or via the general configuration documentation linked from the Pipedream configuration page).

## Pricing
Pricing information is not provided in the available content.