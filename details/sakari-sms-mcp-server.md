# Sakari SMS MCP Server

## Overview
Sakari SMS MCP Server connects Sakari’s cloud SMS messaging platform with MCP-aware clients, enabling automated sending and management of business text messages from applications that support the MCP protocol.

- **Category:** Messaging MCP Servers  
- **Brand:** Sakari  
- **Use cases:** Business SMS, automated text messaging, integrating SMS into chat or workflow tools via MCP

## Features
- **MCP-compatible SMS server** – Exposes Sakari’s SMS capabilities through a standard MCP server endpoint.
- **Static server URL** – Single URL for all MCP clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic integration** – Designed to work with any MCP-aware client; configuration is handled in the client using the shared server URL.
- **Authentication at configuration time** – Authentication occurs when adding the server to your MCP-compatible application (exact method depends on the client and Sakari account setup).
- **Cloud-based infrastructure** – Uses Sakari’s cloud SMS platform for sending and managing business text messages.
- **Business-focused messaging** – Intended for business teams that need to send and manage SMS at scale across different tools.

## Configuration
- Add the MCP server to your MCP-aware chat or automation client using:
  - **Server URL:** `https://mcp.pipedream.net/v2`
- Follow your specific client’s instructions for:
  - Supplying the server URL
  - Completing authentication
  - Enabling SMS-related tools or actions powered by Sakari

## Pricing
- Not specified in the provided content. Consult Sakari or Pipedream documentation for current pricing details.