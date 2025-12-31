# Otter Waiver MCP Server

An MCP (Model Context Protocol) server integration for Otter Waiver that enables waiver management inside compatible MCP clients.

## Overview
- **Type:** MCP server / integration
- **Category:** Business & Commerce MCP Servers
- **Provider:** Pipedream (via Pipedream Connect)
- **Purpose:** Connect Otter Waiver’s waiver management capabilities to MCP-enabled chat or agent applications.

## Features
- **Standard MCP Endpoint**  
  - Single static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL works across all supported MCP clients.

- **Client-Agnostic Integration**  
  - Designed to be added to different MCP-compatible chat clients.  
  - Authentication is performed when adding the server in the client, not via per-client URLs.

- **Waiver Management Focus**  
  - Built around Otter Waiver’s core use case: managing waivers for signing, storage, and compliance workflows (as described in the item metadata).

- **Configuration Guidance**  
  - Central configuration reference available via the Pipedream Connect configuration page.

## Use Cases
- Integrate Otter Waiver into MCP-based chat or agent environments to:
  - Initiate or manage waiver signing workflows.  
  - Access or organize stored waivers.  
  - Support compliance-related waiver handling inside automated assistants.

## Technical Details
- **Protocol:** MCP (Model Context Protocol)
- **Server URL:** `https://mcp.pipedream.net/v2`
- **Authentication:** Performed within the client during server setup.

## Pricing
- No explicit pricing information is provided in the available content. Refer to the Otter Waiver or Pipedream/Workday sites for current pricing details.