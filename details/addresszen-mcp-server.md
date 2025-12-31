# AddressZen MCP Server

## Overview
The AddressZen MCP Server is an MCP-compatible integration that connects to AddressZen to provide address autocomplete and verification capabilities inside tools that support the Model Context Protocol (MCP). It runs as a static MCP server endpoint managed by Pipedream.

- **Category:** API Integration / MCP Servers
- **Provider / Brand:** AddressZen (via Pipedream)
- **Intended use:** Integrate address search, autocomplete, and validation into MCP-enabled chat clients and applications.

## Features
- **Address Autocomplete**
  - Suggests address completions as users type.
  - Designed for integration into MCP-compatible chat clients and tools.

- **Address Verification**
  - Verifies entered addresses via AddressZen’s API.
  - Helps ensure addresses are valid and standardized.

- **MCP-Compatible Server**
  - Exposed via a single static MCP server URL: `https://mcp.pipedream.net/v2`.
  - Can be added to any MCP-compatible application or chat client.
  - Authentication is handled when adding/configuring the server in the client.

- **Centralized Configuration**
  - Connect your AddressZen account through Pipedream.
  - Select the relevant client / chat application from a configuration page.
  - Uses the same static MCP URL for all clients, simplifying setup.

- **Tooling / Actions (via MCP)**
  - Provides a set of “tools” (actions) that can be called by MCP clients for address autocomplete and verification (details are loaded dynamically in the UI).

## Integration & Usage
- **Server URL:**
  - Use `https://mcp.pipedream.net/v2` as the MCP server endpoint.
- **Setup flow:**
  1. Connect your AddressZen account in Pipedream.
  2. Copy the MCP server URL.
  3. Add the MCP server to your MCP-compatible chat client or app.
  4. Authenticate when prompted by the client.

## Pricing
The provided content does not specify any pricing or plans for the AddressZen MCP Server or AddressZen usage. Refer to the AddressZen or Pipedream websites for current pricing details.
