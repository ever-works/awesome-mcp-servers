# iContact MCP Server

**Category:** Business & Commerce – MCP Servers  
**Tags:** email-marketing, campaigns, marketing-automation  
**Source:** https://mcp.pipedream.com/app/icontact

## Overview
The iContact MCP Server is an MCP Server integration that lets MCP-based agents and tools interact with iContact’s email marketing platform. It is designed to support email campaign management and marketing automation workflows via a standard MCP server endpoint.

## Features
- **MCP-based integration with iContact** – Exposes iContact email marketing capabilities to MCP-compatible agents and tools.
- **Static MCP server URL** – Uses a single, static endpoint for all clients:
  - `https://mcp.pipedream.net/v2`
- **Per-client authentication** – Authentication occurs when adding the MCP server to your application, allowing the same URL to be reused across different clients/accounts.
- **Email marketing campaign management** – Supports interaction with iContact’s email marketing features for building and managing campaigns (as described at a high level in the item description).
- **Marketing automation workflows** – Intended to enable automation around email campaigns, such as triggering and managing marketing flows via MCP-compatible tools.
- **Multi-client compatibility** – Can be added to different chat or agent clients that support MCP, using the same configuration URL.

*(The Pipedream UI mentions “available tools” and “actions,” but they are dynamically loaded and not enumerated in the provided content, so specific tools/actions cannot be listed.)*

## Configuration
- Connect an iContact account in Pipedream.
- Select the relevant client in the Pipedream interface.
- Copy and use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the MCP server to any supported MCP client and complete authentication within that client.

## Pricing
No pricing information is provided in the supplied content.