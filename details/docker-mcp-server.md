# Docker MCP Server

## Overview
The Docker MCP Server (Docker Engine MCP Server) is an MCP (Model Context Protocol) server that exposes Docker Engine capabilities to MCP-compatible tools and chat clients. It enables programmatic management of Docker containers, images, and other engine operations through a standardized MCP interface.

- **Name:** Docker MCP Server (Docker Engine MCP Server)
- **Category:** Cloud & DevOps – MCP Servers
- **Brand:** Docker
- **Source URL:** https://mcp.pipedream.com/app/docker_engine
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible Docker access**
  - Provides an MCP Server endpoint for interacting with Docker Engine.
  - Designed to be added directly to MCP-enabled chat clients and applications.

- **Container management (via Docker Engine)**
  - Supports managing Docker containers programmatically (e.g., create, start, stop, inspect, remove), as exposed through Docker Engine.

- **Image management (via Docker Engine)**
  - Enables operations on Docker images (e.g., pull, push, list, remove, inspect), through Docker Engine.

- **Other engine operations**
  - Gives tools access to additional Docker Engine capabilities (e.g., networks, volumes, and other engine-level operations) as supported by the underlying Docker Engine API.

- **Static MCP server URL**
  - Uses a single static base URL for all clients: `https://mcp.pipedream.net/v2`.
  - Authentication is handled when you add the server to your specific application or client.

- **Client-agnostic integration**
  - Works with multiple MCP-compatible chat clients and applications.
  - Documentation available per client (via the configuration page) for setup steps.

- **Hosted by Pipedream Connect**
  - The MCP server is operated and provided through Pipedream Connect’s infrastructure.

## Integration
- Add the MCP server URL `https://mcp.pipedream.net/v2` to your MCP-compatible chat client or app.
- Follow client-specific instructions from the configuration documentation (linked on the source page).
- Authenticate during setup within your client or application.

## Pricing
The provided content does not include any pricing or plan information for the Docker MCP Server. Pricing, if applicable, is not specified on the referenced page.