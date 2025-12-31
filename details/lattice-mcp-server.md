# Lattice MCP Server

An MCP (Model Context Protocol) server integration for Lattice’s people and performance management platform, provided via Pipedream.

## Overview

The Lattice MCP Server allows compatible MCP-enabled applications (such as chat clients or AI assistants) to connect to a Lattice account through a static MCP server URL. Once configured, the application can interact with Lattice’s people management and performance data via the tools exposed by the server.

- **Category:** Business & Commerce – MCP Servers
- **Use cases:** HR workflows, people management, performance management integrations
- **Provider:** Pipedream
- **Target platform:** Lattice (people management and performance platform)

## Features

- **Static MCP Server Endpoint**  
  - Uses a single static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Works for all Lattice clients; authentication is handled when adding the server to your application.

- **Lattice Account Integration**  
  - Connects to an existing Lattice account.  
  - Supports selecting the appropriate Lattice client within the configuration flow.

- **MCP-Compatible Integration**  
  - Designed to be added as an MCP server to compatible chat or AI applications.  
  - Uses the Model Context Protocol to expose Lattice-related tools and actions.

- **Configurable via Pipedream**  
  - Configuration handled through Pipedream’s interface ("Configure Lattice").  
  - Account connection and client selection done during setup.

- **Tooling Exposure**  
  - Exposes “available tools” (actions) related to Lattice through the MCP server.  
  - Tools list is dynamically loaded by the Pipedream integration (exact tools not enumerated in the provided content).

## Setup

1. **Connect Lattice in Pipedream**  
   - Go to the Lattice MCP Server page on Pipedream.  
   - Connect your Lattice account and select your client.

2. **Copy MCP Server URL**  
   - Use the static URL: `https://mcp.pipedream.net/v2`.

3. **Add Server to Your Application**  
   - In your MCP-compatible chat or AI client, add a new MCP server using the URL above.  
   - Authenticate when prompted.  
   - Optionally refer to the full Configuration page on Pipedream for client-specific steps.

## Pricing

The provided content does not include any pricing or plan information for the Lattice MCP Server integration.