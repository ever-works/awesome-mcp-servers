# Phaxio MCP Server

## Overview
Phaxio MCP Server is an MCP-compatible server that connects applications to the Phaxio fax API, enabling sending and receiving faxes via a standardized MCP protocol endpoint.

- **Type:** MCP server / integration
- **Category:** Messaging MCP servers
- **Provider / Brand:** Phaxio (hosted on Pipedream)
- **Primary use case:** Programmatic fax communication via the Phaxio API through a unified MCP server URL

## Features
- **Fax communication via MCP**
  - Send faxes using the Phaxio fax API through the MCP protocol.
  - Receive faxes from Phaxio within MCP-compatible clients or applications.

- **Single static MCP endpoint**
  - Uses a single static server URL for all clients: `https://mcp.pipedream.net/v2`.
  - Same URL can be reused across different MCP-compatible chat clients and applications.

- **Account-based authentication**
  - Authentication occurs when adding the MCP server to your application, tied to your Phaxio / Pipedream account.
  - Allows per-account configuration of fax capabilities.

- **Client-agnostic setup**
  - Designed to be added to multiple chat or application clients.
  - Each client can follow its own “add server” flow while using the same MCP server URL.

- **Configuration via Pipedream**
  - Configure Phaxio connectivity through the Pipedream interface.
  - Centralizes account connection and client selection.

> Note: The page references "Available tools" and "Loading actions..." but does not list specific tools or actions; only the general capability to send/receive fax via the Phaxio API is explicitly documented.

## Integration Details
- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Setup steps (high-level):**
  1. Connect or configure your Phaxio account in Pipedream.
  2. Copy the static MCP server URL.
  3. Add the server URL to your MCP-compatible app or chat client.
  4. Authenticate when prompted by your client/application.

## Pricing
The provided content does not include any pricing or plan information for the Phaxio MCP Server or underlying Phaxio/Pipedream services.