# Hippo Video MCP Server

## Overview
Hippo Video MCP Server is an integration that exposes Hippo Video’s interactive B2B video customer experience platform through the Model Context Protocol (MCP). It allows MCP-compatible applications (such as AI chat clients) to create, send, and track B2B videos via a standardized server endpoint.

## Key Details
- **Name:** Hippo Video MCP Server  
- **Category:** Media Processing MCP Servers  
- **Provider / Brand:** Hippo Video (via Pipedream)  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Use Cases:** B2B video creation, delivery, and performance tracking within MCP-enabled apps

## Features
- **MCP-based access to Hippo Video**  
  Exposes Hippo Video functionality through the Model Context Protocol so tools and chat clients can interact with the platform programmatically.

- **B2B video CX workflows**  
  Designed around interactive video customer experience (CX) for B2B use cases, including creating, sending, and tracking videos.

- **Single static server URL**  
  Uses a static MCP server endpoint (`https://mcp.pipedream.net/v2`) that works for all clients; authentication is handled when adding the server to the application.

- **Client-agnostic integration**  
  Can be added to different MCP-compatible chat clients or applications by configuring the same server URL.

- **Configuration via Pipedream**  
  Configuration flow provided by Pipedream, including connecting a Hippo Video account before using the server.

> Note: The onsite content references “available tools” and “actions,” but does not enumerate specific named tools or operations.

## Setup / Configuration
1. Connect a Hippo Video account via Pipedream.  
2. Copy the MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add the server to an MCP-compatible app or chat client and authenticate as prompted.  
4. Use the exposed tools/actions to create, send, and track B2B videos from within the client.

## Pricing
The provided content does not include any pricing information or plan details for Hippo Video MCP Server.