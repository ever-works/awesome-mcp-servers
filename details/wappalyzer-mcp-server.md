# Wappalyzer MCP Server

Identify and report the technologies used on websites via the Wappalyzer API, exposed as an MCP (Model Context Protocol) server.

## Overview
- **Name:** Wappalyzer MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Brand:** Wappalyzer (via Pipedream Connect)  
- **Purpose:** Detect and analyze technologies used on websites (e.g., frameworks, CMS, analytics tools) and make them available to MCP-compatible chat clients and applications.

## Features
- **Technology detection on websites**  
  - Identifies technologies used on a given website (e.g., libraries, frameworks, CMS, analytics, e‑commerce platforms, etc.).  
  - Reports detected technologies in a structured form suitable for use within MCP clients.

- **MCP server integration**  
  - Exposes Wappalyzer functionality as an MCP server so it can be consumed by MCP-compatible chat and AI clients.  
  - Designed for use inside applications that support the Model Context Protocol.

- **Static MCP server endpoint**  
  - Single static base URL for all clients:  
    `https://mcp.pipedream.net/v2`  
  - Same endpoint works across different MCP-compatible clients.

- **Authentication via client configuration**  
  - Authentication is performed when adding the server to your MCP-enabled application (credentials / keys configured in the client, not embedded in the URL).

- **Client-agnostic setup**  
  - Can be added to different chat clients that support MCP.  
  - Configuration instructions are available per client via the associated configuration pages.

- **Hosted and powered by Pipedream Connect**  
  - The MCP server is operated by Pipedream, which provides the infrastructure for the Wappalyzer integration.

## Configuration & Usage
- Use the MCP server URL in your MCP-compatible app configuration:  
  - **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- Complete authentication within your client’s MCP settings.  
- Once configured, call the Wappalyzer MCP tools/endpoints from your client to analyze websites.

## Pricing
The provided content does not list any pricing or plans for the Wappalyzer MCP Server. Consult the Pipedream or Wappalyzer documentation / dashboards for current pricing details.
