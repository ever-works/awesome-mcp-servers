# BunnyDoc MCP Server

**Category:** Document Management MCP Servers  
**Brand:** BunnyDoc  
**Slug:** bunnydoc-mcp-server

## Description
BunnyDoc MCP Server is an integration that exposes BunnyDoc’s legally binding electronic signature and document workflow capabilities through the Model Context Protocol (MCP). It allows compatible chat or AI clients to connect to BunnyDoc and work with e-signature processes and document workflows via a standardized MCP server endpoint.

## Features
- **MCP-based integration:** Provides a static MCP server endpoint (`https://mcp.pipedream.net/v2`) that can be added to any compatible chat or AI application.
- **Legally binding e-signatures:** Interfaces with BunnyDoc’s electronic signature functionality designed for legally binding signatures.
- **Document workflows:** Enables access to BunnyDoc’s document workflow capabilities through MCP tools (actions are dynamically loaded when connected).
- **Account connection flow:** Requires connecting a BunnyDoc account and selecting a client before using tools.
- **Client-agnostic server URL:** The same MCP server URL works for all supported clients; authentication occurs when the server is added to the application.
- **Configuration guidance:** Supports setup via client-specific instructions and a detailed configuration page.

## Technical Details
- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Integration host:** Pipedream MCP platform
- **Usage pattern:**
  1. Connect a BunnyDoc account.
  2. Copy the static MCP server URL.
  3. Add the server to a compatible chat/AI client.
  4. Authenticate within the client and use available MCP tools for BunnyDoc.

## Pricing
Pricing information is not provided in the available content.