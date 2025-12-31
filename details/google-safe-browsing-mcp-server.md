# Google Safe Browsing MCP Server

**Category:** Security & Attestation MCP Servers  
**Slug:** `google-safe-browsing-mcp-server`  
**Brand:** Google  
**Source URL:** https://mcp.pipedream.com/app/google_safebrowsing

![Google Safe Browsing](https://safebrowsing.google.com/images/safebrowsing-hero.png)

## Overview
The Google Safe Browsing MCP Server exposes Google’s Safe Browsing service to MCP-compatible tools and clients. It allows applications to check URLs against Google’s continuously updated lists of unsafe web resources for security-focused use cases.

## Features
- **URL safety checks**: Query URLs against Google Safe Browsing lists to detect unsafe or malicious web resources.
- **Continuously updated threat data**: Uses Google’s regularly refreshed lists of unsafe sites for more current threat detection.
- **Static MCP endpoint**: Single, static MCP server URL for all clients:
  - `https://mcp.pipedream.net/v2`
- **MCP-compatible integration**: Designed to be added as an MCP server to chat or other MCP-enabled clients.
- **Centralized configuration**: Works with a generic configuration flow via the Pipedream MCP configuration page (per linked documentation).

## Usage
- Add the MCP server URL `https://mcp.pipedream.net/v2` to your MCP-enabled application.
- Authenticate as part of the server setup process in your client.
- Use available MCP tools (as exposed by the client) to perform Safe Browsing URL checks.

## Pricing
- No pricing information is provided in the available content.

## Tags
- Security  
- Threat Intelligence  
- URL Checking