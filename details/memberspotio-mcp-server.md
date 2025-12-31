# Memberspot.io MCP Server

**Category:** Documentation & Learning Resources  
**Tags:** e-learning, courses, training

## Overview
The Memberspot.io MCP Server exposes the Memberspot e-learning platform through the Model Context Protocol (MCP), allowing applications (such as chat clients) to access and interact with Memberspot-based training content for employees and customers.

## Features
- **MCP-based access:** Provides a static MCP server endpoint (`https://mcp.pipedream.net/v2`) that can be added to any MCP-compatible application.
- **Universal server URL:** A single, static URL works for all Memberspot.io clients; specific access is controlled via authentication when configuring the server in your app.
- **Integration with chat clients:** Designed to be added to various chat clients so they can access Memberspot.io learning resources via MCP.
- **Configuration guidance:** Linked configuration instructions to help users connect their Memberspot.io account and select the appropriate client.
- **Tool-based actions (via MCP):** Exposes “available tools” (MCP actions) for interacting with Memberspot.io, such as accessing or managing e-learning resources (the page indicates tools are loaded dynamically, though specific tools are not listed).

## Technical Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Authentication:** Performed when adding the MCP server to your application; the same URL is used regardless of client, with auth determining accessible resources.

## Pricing
No pricing information is provided in the available content.