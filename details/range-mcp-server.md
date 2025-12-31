# Range MCP Server

An MCP (Model Context Protocol) server that connects AI agents to Range, enabling access to team check-ins, updates, and work coordination data.

## Overview
- **Name:** Range MCP Server  
- **Category:** Project management MCP servers  
- **Provider / Brand:** Range (via Pipedream Connect)  
- **Purpose:** Gives AI agents programmatic access to Range data for remote and hybrid team coordination.

## Server URL
- **MCP Server Endpoint (static for all clients):**  
  `https://mcp.pipedream.net/v2`
- Authentication is handled when adding the server to the client/application.

## Features
- **Range integration for AI agents**  
  - Connects to Range so AI agents can access:  
    - Team check-ins  
    - Team updates  
    - Work coordination data
- **Standard MCP server behavior**  
  - Exposes Range data and actions via the Model Context Protocol for compatible clients.
- **Static connection URL**  
  - Single, static MCP endpoint (`https://mcp.pipedream.net/v2`) usable across different MCP-compatible chat clients and tools.
- **Client-agnostic setup**  
  - Designed to work with multiple chat clients that support MCP.  
  - Configuration guidance is available via a dedicated configuration page (client-specific setup instructions).
- **Pipedream Connect infrastructure**  
  - Hosted and powered by Pipedream Connect, handling connectivity between MCP clients and Range’s APIs.

## Usage & Configuration
- **Add to MCP-compatible apps:**  
  - Use the static URL when adding a new MCP server in your client.  
  - Authenticate with Pipedream/Range when prompted during setup.
- **Configuration reference:**  
  - Additional configuration details and client-specific instructions are available on the linked Configuration page (not included in this summary).

## Pricing
- Not specified in the provided content.