# Stannp MCP Server

An MCP (Model Context Protocol) server that lets applications create and send postal direct mail campaigns (letters and postcards) via Stannp.

## Overview
- **Item type:** MCP server / integration
- **Category:** Business & Commerce – MCP Servers
- **Provider / Brand:** Stannp (via Pipedream Connect)
- **Use case:** Programmatic creation and sending of physical direct mail (letters, postcards) from MCP-compatible clients.

## Features
- **MCP-compatible endpoint**: Exposed via a static MCP server URL usable by any compatible client.
- **Direct mail campaign support**: Designed specifically for postal direct mail, including:
  - Letters
  - Postcards
- **Client-agnostic configuration**: Same base URL for all clients; authentication is handled when adding the server to each application.
- **Hosted by Pipedream**: Runs on Pipedream’s infrastructure (Pipedream Connect).

## Technical Details
- **MCP server URL**: `https://mcp.pipedream.net/v2`
- **Authentication**: Performed when adding/configuring the MCP server in your client (details depend on the client; not specified in the provided content).

## Getting Started
- Use the static URL `https://mcp.pipedream.net/v2` when adding the MCP server to your MCP-enabled chat client or application.
- Follow your specific client’s instructions for adding an MCP server and completing authentication.
- Additional configuration details are available on the referenced configuration page (not included in the provided content).

## Pricing
- Not specified in the provided content.