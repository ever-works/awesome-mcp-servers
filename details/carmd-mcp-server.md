# CarMD MCP Server

**Category:** Business & Commerce – MCP Servers  
**Brand:** CarMD  
**Slug:** `carmd-mcp-server`

## Overview
CarMD MCP Server is an MCP (Model Context Protocol) server that connects MCP-compatible tools and chat clients to CarMD services. It exposes OBD2-based automotive diagnostics, data, and related applications, helping reduce car ownership and maintenance costs by leveraging vehicle OBD2 port capabilities.

The server is hosted via Pipedream Connect and is available through a static MCP endpoint.

## MCP Endpoint
- **Server URL:** `https://mcp.pipedream.net/v2`  
  This static URL is used by all clients; authentication is performed when adding the server to your specific application.

## Features
- **MCP-compatible server**
  - Implements a standardized MCP interface for integration with MCP-enabled chat clients and tools.
- **Access to CarMD automotive services**
  - Interfaces with CarMD’s software service solutions, surfacing their data/products/apps through MCP.
- **OBD2-based diagnostics integration**
  - Designed to leverage OBD2 port capabilities for vehicle diagnostics and related data.
- **Automotive data access**
  - Provides access to automotive information that can be used by tools to assist with car maintenance and ownership decisions.
- **Cost-reduction focus**
  - Targets use cases that help reduce car ownership and maintenance costs using diagnostic and vehicle data.
- **Static, shared endpoint**
  - Uses a single static URL (`https://mcp.pipedream.net/v2`) for all clients, simplifying configuration.
- **Authentication at client setup**
  - Authentication is handled when adding the MCP server to your application or chat client (details provided by the client’s configuration flow).
- **Pipedream Connect integration**
  - Hosted and powered by Pipedream Connect, benefiting from its infrastructure and configuration tooling.

## Integration & Configuration
- Add the MCP server to your chat client or MCP-compatible app using the static URL.
- Client-specific setup instructions are available via the configuration resources linked from the Pipedream app page (e.g., “Configuration” page for detailed steps).

## Pricing
No pricing information is provided in the available content.