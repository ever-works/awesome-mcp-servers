# WebinarKit MCP Server

## Overview
WebinarKit MCP Server is a Model Context Protocol (MCP) server that connects AI agents to WebinarKit. It enables programmatic creation and management of automated, like-live, and just-in-time webinar funnels through a standardized MCP endpoint.

- **Category:** Business & Commerce – MCP Servers
- **Brand:** WebinarKit
- **Slug:** `webinarkit-mcp-server`
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP integration for WebinarKit**  
  - Exposes WebinarKit functionality via the MCP protocol so AI agents and MCP-compatible clients can interact with webinar funnels.
- **Webinar funnel management**  
  - Supports creation and management of webinar funnels, including:  
    - Automated webinars  
    - Like-live webinars  
    - Just-in-time webinars
- **Single static server endpoint**  
  - Uses a single static URL (`https://mcp.pipedream.net/v2`) for all clients.  
  - Authentication handled when adding the MCP server in the client application.
- **Multi-client compatibility**  
  - Designed to be added to various chat or MCP-compatible applications as a server.  
  - Client-specific setup instructions are accessible from the configuration flow.
- **Centralized configuration**  
  - Account connection and client selection handled through a configuration interface.  
  - Provides a dedicated configuration page for full setup details.

## Integration Details
- **Endpoint type:** MCP server
- **Authentication:** Performed when the server is added to the application (details handled in client/configuration flow).
- **Usage flow:**  
  1. Connect WebinarKit account in the configuration interface.  
  2. Copy MCP server URL `https://mcp.pipedream.net/v2`.  
  3. Add the server URL to the chosen MCP-compatible chat client.  
  4. Use available MCP tools/actions to create and manage webinar funnels.

## Pricing
The provided content does not list any pricing or plans for WebinarKit MCP Server.