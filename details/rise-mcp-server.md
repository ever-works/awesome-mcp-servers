# Rise MCP Server

## Overview
Rise MCP Server is an MCP-compatible server that connects AI tools with the Rise all‑in‑one training system. It enables programmatic creation, delivery, and management of online training content through the Model Context Protocol (MCP), so AI assistants and workflows can work directly with Rise training resources.

- **Category:** Business & Commerce → MCP Servers  
- **Use cases:** Integrate Rise with AI agents, automate training operations, and manage LMS content via MCP-compatible clients.

## MCP Server Endpoint
- **MCP base URL:** `https://mcp.pipedream.net/v2`  
- This is a static URL used by all clients; authentication is handled when adding the server to your MCP-compatible application or chat client.

## Features
- **MCP compatibility**  
  - Exposes Rise training capabilities as an MCP server for use with compatible AI/chat clients and tools.

- **Integration with Rise training system**  
  - Connects to the Rise LMS / training platform.  
  - Intended to allow programmatic access to:
    - Create online training content.  
    - Deliver courses and training experiences.  
    - Manage training content and related resources.

- **Static, reusable server URL**  
  - Uses a single, static MCP endpoint (`https://mcp.pipedream.net/v2`) that works across all clients, simplifying configuration.

- **Client-agnostic setup**  
  - Can be added to different MCP-compatible chat clients or applications.  
  - Configuration is handled per client (authentication provided when adding the server).

- **Pipedream Connect integration**  
  - Hosted and powered by Pipedream Connect, enabling use within Pipedream’s broader automation and integration ecosystem.

## Setup & Configuration
- Add the server URL `https://mcp.pipedream.net/v2` to your MCP-capable app or chat client.  
- Authenticate during the add/configuration step in the client.  
- Detailed, client-specific setup instructions are available via the platform’s configuration documentation (not reproduced here).

## Pricing
The provided content does not list any pricing or plans for Rise MCP Server.