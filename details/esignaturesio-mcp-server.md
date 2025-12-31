# eSignatures.io MCP Server

## Overview
The **eSignatures.io MCP Server** exposes eSignatures.io electronic signature workflows to MCP-compatible clients, enabling creation and management of signable documents across devices via a single MCP endpoint.

- **Item type:** MCP server integration
- **Category:** Business & Commerce – MCP Servers
- **Brand:** eSignatures.io
- **Slug:** `esignaturesio-mcp-server`
- **MCP server URL:** `https://mcp.pipedream.net/v2`

## Features
- **Electronic signature collection**
  - Supports collecting legally binding electronic signatures.
  - Works across devices (e.g., desktop, tablet, mobile).
- **MCP server integration**
  - Exposes eSignatures.io workflows through the Model Context Protocol (MCP).
  - Accessible via a single static URL that works for all compatible clients.
- **Document workflow management**
  - Provides access to signable document workflows (creation, sending, and management) through MCP clients.
- **Static endpoint for all clients**
  - Uses one shared MCP endpoint (`https://mcp.pipedream.net/v2`) for different chat / MCP-enabled applications.
- **Authentication at client setup**
  - Authentication is handled when adding the server to your application or chat client.
- **Client-agnostic usage**
  - Can be added to various MCP-compatible chat clients and tools, following their configuration instructions.

## Integration & Configuration
- Add the MCP server by pointing your MCP-compatible client to:
  - `https://mcp.pipedream.net/v2`
- Configuration details and client-specific setup steps are available via the provider’s configuration documentation (referenced as the full Configuration page in the source content).

## Pricing
- No pricing information is provided in the available content.