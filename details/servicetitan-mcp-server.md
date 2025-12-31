# ServiceTitan MCP Server

Home and commercial software for the trades, exposed through an MCP-compatible server.

## Overview
The ServiceTitan MCP Server provides a Model Context Protocol (MCP) interface to ServiceTitan, enabling applications and chat-based tools to interact with ServiceTitan’s home and commercial trade service management capabilities (such as dispatching, jobs, and customer records) through a standardized MCP endpoint.

- **Type:** MCP Server / integration
- **Category:** Business & Commerce – MCP Servers
- **Brand:** ServiceTitan
- **Provider/Host:** Pipedream Connect
- **Primary Use Cases:** Field service operations, dispatch, job management, CRM-style customer data access via MCP

## MCP Endpoint
- **Base MCP Server URL (static for all clients):**
  - `https://mcp.pipedream.net/v2`
- The same URL is used by all clients; authentication is handled when you add the server to your MCP-compatible application or chat client.

## Features
- **Standardized MCP Access**
  - Exposes ServiceTitan functionality through a single MCP-compatible server endpoint.
  - Works with any MCP-capable client or chat application.

- **Shared Static URL**
  - One static URL (`https://mcp.pipedream.net/v2`) for all users.
  - No per-tenant or per-user URL required; configuration happens at the client level.

- **Authentication via Client Configuration**
  - Authentication is performed when adding the MCP server to your application or chat client.
  - Keeps the server URL stable while allowing per-user authentication and permissions.

- **Configuration Guidance**
  - Can be added to various chat clients that support MCP.
  - Additional configuration details are available via the provider’s configuration documentation (referenced as a “Configuration page”).

- **ServiceTitan Domain Focus**
  - Designed to connect with ServiceTitan’s home and commercial trade service management features.
  - Intended to provide MCP-level access to:
    - Dispatching and scheduling operations.
    - Job-related data and workflows.
    - Customer records and related CRM-style information.

## Pricing
Pricing details are not provided in the available content. Refer to the provider’s site or ServiceTitan/Pipedream documentation for current pricing information.
