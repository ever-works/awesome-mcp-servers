# Frame.io MCP Server

Video review and collaboration MCP server integration for Frame.io, provided via Pipedream Connect.

## Overview
The Frame.io MCP Server exposes Frame.io’s video review and collaboration capabilities to AI/chat clients through a static MCP endpoint. Clients authenticate when adding the server to their application, enabling automated or AI-assisted workflows around video review, feedback collection, and review management.

## MCP Server Endpoint
- **Server URL:** `https://mcp.pipedream.net/v2`
- **Type:** Static MCP server URL (same for all clients)
- **Authentication:** Performed when adding the server inside the client/application

## Features
- **Frame.io platform integration**
  - Connects AI tools and chat-based clients to Frame.io’s video review and collaboration platform via MCP.
  - Designed for media workflows involving video, feedback, and approvals.

- **MCP compatibility**
  - Exposes an MCP server endpoint that can be added to compatible chat or AI clients.
  - Uses a single static URL for all clients, simplifying configuration.

- **Authentication at client setup**
  - Users authenticate when adding the server to their chosen application, enabling secure access to Frame.io resources.

- **Configuration guidance**
  - Can be added to different chat clients (instructions referenced per client).
  - Additional configuration details available via a dedicated configuration page (not reproduced here).

- **Pipedream Connect infrastructure**
  - Hosted and operated by Pipedream using Pipedream Connect.

> Note: The underlying description indicates support for uploading media, collecting feedback, and managing review workflows via MCP, though the page content does not list each operation explicitly.

## Usage
- Add `https://mcp.pipedream.net/v2` as an MCP server in your compatible chat/AI client.
- Complete authentication when prompted by your client.
- Use the client’s MCP tooling interface to interact with Frame.io-related tools and workflows.

## Pricing
- The provided content does **not** list any pricing or plans for the Frame.io MCP Server or for Pipedream Connect. Pricing, if applicable, would need to be obtained from the provider’s main site or product pages.