# Reverse Contact MCP Server

**Category:** Business & Commerce MCP Servers  
**Slug:** reverse-contact-mcp-server  
**Brand:** Reverse Contact

## Overview
Reverse Contact MCP Server is a Model Context Protocol (MCP) server that lets MCP-compatible agents and chat clients look up LinkedIn profiles from email addresses via the Reverse Contact service. It is delivered through Pipedream Connect and accessed via a static MCP endpoint.

## Features
- **LinkedIn lookup from email**  
  - Resolve an email address to a corresponding LinkedIn profile using the Reverse Contact service.
- **MCP-compatible server**  
  - Exposes Reverse Contact functionality as an MCP server for use by MCP agents and chat clients.
- **Static server URL**  
  - Single, static endpoint for all clients:  
    `https://mcp.pipedream.net/v2`
- **Per-client authentication**  
  - Authentication is performed when adding the server to each application/client (details handled during client setup).
- **Client-agnostic integration**  
  - Designed to work with any MCP-enabled chat client that can consume an MCP server URL.
- **Configuration guidance**  
  - Additional setup details are available on a dedicated configuration page (via Pipedream Connect).

## Usage
- Add the MCP server URL `https://mcp.pipedream.net/v2` to your MCP-compatible chat client.
- Authenticate within your client during the server addition process.
- Use the server’s tools/endpoints to look up LinkedIn profiles by providing email addresses.

## Pricing
- No pricing information is provided in the available content.