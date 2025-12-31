# SmartEngage MCP Server

## Overview
The **SmartEngage MCP Server** connects MCP-based AI clients to SmartEngage’s engagement and marketing platform. It enables AI workflows to perform omnichannel engagement and marketing operations via a standardized MCP server endpoint.

- **Name:** SmartEngage MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Brand:** SmartEngage  
- **Website / Source:** https://mcp.pipedream.com/app/smartengage

## Features
- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL usable by any compatible client: `https://mcp.pipedream.net/v2`.
  - Designed to be added to MCP-capable chat / AI applications.

- **Account connection & configuration**  
  - Connects a SmartEngage account through the Pipedream interface.  
  - Allows selection of a specific SmartEngage client (workspace/account) after connecting.

- **Authentication at client level**  
  - Authentication occurs when the server is added to the MCP-enabled application, not per-URL, so the same URL can serve multiple clients.

- **Omnichannel engagement operations (via SmartEngage)**  
  - Integrates with SmartEngage’s engagement and marketing service to support omnichannel engagement from AI workflows (e.g., messaging to customers across multiple channels).  
  - Enables AI-driven marketing / engagement use cases from within chat-based tools.

- **Tooling exposure via MCP**  
  - Exposes SmartEngage actions as “tools” to MCP clients (listed as “Available tools” in the Pipedream app; specific tools are dynamically loaded).  
  - Allows AI agents to call these tools programmatically during conversations.

- **Configuration guidance**  
  - Provides in-app instructions for adding the MCP server to various chat clients.  
  - Links to a full configuration page for more detailed setup steps.

## Requirements
- A SmartEngage account.  
- An MCP-compatible client or application that can register external MCP servers.  
- Ability to configure the server URL `https://mcp.pipedream.net/v2` and complete authentication.

## Technical Details
- **Protocol:** Model Context Protocol (MCP) server.  
- **Endpoint:** Static, shared URL for all SmartEngage clients.  
- **Host platform:** Pipedream (server delivered through Pipedream’s MCP infrastructure).

## Pricing
No pricing details or plan information are provided in the available content. Use of the SmartEngage MCP Server may be subject to SmartEngage and/or Pipedream pricing; consult their official sites for current terms.