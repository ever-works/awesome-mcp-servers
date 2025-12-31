# Campayn MCP Server

## Overview
The Campayn MCP Server is an MCP-compatible integration endpoint that connects your applications or chat clients to Campayn’s email marketing platform. It provides a static MCP server URL that you can add to any supported client to manage and track email marketing campaigns via Campayn.

- **Type:** MCP Server / Integration
- **Category:** Business & Commerce – MCP Servers
- **Use case:** Connect tools and chat clients to Campayn for email marketing operations (creating, sending, and tracking campaigns).

## Features
- **MCP-compatible server endpoint**  
  - Exposes Campayn functionality through the Model Context Protocol (MCP) so MCP-aware clients can interact with Campayn.

- **Static server URL**  
  - Single static endpoint for all clients:  
    `https://mcp.pipedream.net/v2`  
  - Same URL works across different chat clients and applications.

- **Account connection flow**  
  - Connect your Campayn account through Pipedream’s configuration UI.  
  - Select a client after connecting to start using Campayn from that environment.

- **Client-agnostic configuration**  
  - Works with multiple chat clients; you select your specific client to see tailored setup instructions.  
  - Server is added to the client using the provided MCP URL and authentication.

- **Authentication at client setup**  
  - Authentication happens when adding the server to your application or chat client, not via per-client URLs.

- **Central configuration page**  
  - Dedicated configuration page on Pipedream for viewing setup details and available actions/tools.

- **Tools (actions) exposure**  
  - The server is designed to expose “available tools” (actions) related to Campayn (e.g., create, send, or track email campaigns) once the account is connected.  
  - Tools are loaded dynamically within the configuration interface.

## Pricing
The provided content does not list any pricing information for the Campayn MCP Server or associated plans.