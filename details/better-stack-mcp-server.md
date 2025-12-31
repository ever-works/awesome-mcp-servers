# Better Stack MCP Server

**Category:** Monitoring  
**Brand:** Better Stack  
**Slug:** `better-stack-mcp-server`

## Overview
The Better Stack MCP Server exposes Better Stack observability and incident management capabilities to MCP-compatible clients. It lets tools and chat-based agents access monitoring, logging, and incident data through the Model Context Protocol.

Core use cases include:
- Observability for applications and infrastructure
- Accessing logs for troubleshooting and debugging
- Working with incident data for incident management workflows

## MCP Server URL
- **MCP Server Endpoint (static for all clients):**
  ```
  https://mcp.pipedream.net/v2
  ```
- Authentication is performed when you add the server to your MCP-compatible application.

## Features
- **MCP-compatible server**
  - Exposes Better Stack functionality via the Model Context Protocol.
  - Usable from any MCP-capable client or chat application.

- **Observability integration**
  - Access to Better Stack monitoring data for systems and applications.
  - Support for examining system health and performance via MCP tools.

- **Logging access**
  - Tools to query and retrieve logs from Better Stack.
  - Suitable for debugging and root‑cause analysis from within MCP clients.

- **Incident management data**
  - Access to incidents tracked in Better Stack.
  - Enables workflows around incident investigation and resolution inside MCP-compatible tools.

- **Static server URL**
  - Single, static endpoint (`https://mcp.pipedream.net/v2`) works across all supported clients.
  - Simplifies configuration and reuse across different MCP tools.

- **Client-agnostic setup**
  - Can be added to multiple chat clients or applications that support MCP.
  - Documentation available via a configuration page (for step‑by‑step setup per client).

## Integration & Setup
- Add the server URL to your MCP-compatible chat client or application.
- Authenticate during the add/connect step (authentication details depend on the client and Better Stack account configuration).
- Optional: Refer to the dedicated configuration page for client-specific instructions.

## Pricing
The provided content does not specify any pricing or plan details for the Better Stack MCP Server.