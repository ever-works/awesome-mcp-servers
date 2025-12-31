# Nextcloud MCP Server

**Category:** File Management MCP Servers  
**Brand:** Nextcloud  
**Slug:** `nextcloud-mcp-server`

## Overview
The Nextcloud MCP Server is an MCP Server integration that allows AI agents and MCP-compatible clients to interact with data stored in a self-hosted Nextcloud instance (files and collaboration data) through Pipedream MCP. It is designed to make remote collaboration and file storage access available programmatically from chat or agent environments.

## Features
- **MCP Server for Nextcloud**  
  - Provides a Model Context Protocol (MCP) server endpoint that exposes Nextcloud resources to MCP-compatible clients.
- **Static MCP Endpoint**  
  - Uses a single static server URL for all clients:  
    - `https://mcp.pipedream.net/v2`
- **Account-based Configuration**  
  - Connect a Nextcloud account via Pipedream MCP.  
  - Configure access once, then reuse the same server URL across multiple clients.
- **Client-agnostic Integration**  
  - Works with various MCP-compatible chat or agent clients.  
  - Each client authenticates when the server is added to the application.
- **AI Agent Access to Nextcloud**  
  - Enables AI agents to interact with self-hosted collaboration and file-sharing data stored in Nextcloud.  
  - Intended for remote collaboration and file storage workflows.
- **Configuration Documentation**  
  - Full setup and configuration details are available on a dedicated configuration page (linked from the app).

> Note: The page references “Available tools” and “Loading actions…”, indicating tools/actions are exposed via the MCP server, but specific tool names or capabilities are not listed in the provided content.

## Setup Steps (from provided content)
1. **Configure Nextcloud** in Pipedream MCP by connecting your account.  
2. **Copy the MCP Server URL:** `https://mcp.pipedream.net/v2`.  
3. **Add the MCP Server to Your App**:  
   - Select your MCP-compatible chat or agent client.  
   - Add the server URL and authenticate when prompted.  
4. Optionally consult the **full Configuration page** for detailed instructions.

## Pricing
The provided content does not include any pricing information or plan details for the Nextcloud MCP Server or related Pipedream services.