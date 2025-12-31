# Api Void MCP Server

**Category:** Security & Attestation MCP Servers  
**Brand:** apivoid  
**Source URL:** https://mcp.pipedream.com/app/api_void  
**MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Description
Api Void MCP Server is a Model Context Protocol (MCP) server that exposes APIVoid’s threat analysis and reputation APIs through Pipedream. It provides programmatic access to security intelligence for IP addresses, domains, and related indicators to help detect and prevent malicious activity.

## Features
- **Threat analysis APIs**
  - Access to APIVoid’s threat detection and prevention capabilities through MCP.
- **IP reputation lookup**
  - Query IP addresses for reputation and potential malicious activity.
- **Domain reputation lookup**
  - Query domains for reputation and risk assessment.
- **Additional reputation and threat data**
  - Support for “IP, domain, etc.” indicators (other related reputation endpoints exposed by APIVoid via MCP).
- **Static MCP server URL**
  - Uses a single static endpoint (`https://mcp.pipedream.net/v2`) compatible with all supported MCP clients.
- **Client-agnostic integration**
  - Can be added to different chat or MCP-compatible applications; authentication is completed when the server is added to the app.
- **Configuration support via Pipedream**
  - Full configuration details available through Pipedream’s configuration pages (e.g., adding the server, authentication setup).

## Usage
- Add the MCP server to an MCP-compatible chat client or application using:
  - **Server URL:** `https://mcp.pipedream.net/v2`
- Authenticate within your client when prompted to enable access to APIVoid’s threat intelligence endpoints.

## Pricing
No pricing information is provided in the available content. Refer to the source or provider for current pricing details.