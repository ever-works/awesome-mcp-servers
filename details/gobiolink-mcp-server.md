# gobio.link MCP Server

An MCP server for gobio.link that enables workflows around biolink-based lead generation and social media traffic routing.

## Overview
- **Type:** MCP server (for Model Context Protocol–compatible clients)
- **Provider:** gobiolink, powered by Pipedream Connect
- **Category:** Business & Commerce – MCP Servers
- **Primary use cases:**
  - Lead generation using biolinks
  - Routing and organizing social media traffic via a central biolink
  - Sharing curated content on social media and directing users to a biolink

## Features
- **Biolink-centric lead generation**
  - Supports workflows that use gobio.link biolinks to capture and generate leads.
  - Designed to help route user traffic from social channels into lead funnels.

- **Social media traffic routing**
  - Enables directing social media users to a gobio.link biolink “with absolute ease”.
  - Can be used in MCP workflows to consolidate multiple destinations behind a single biolink.

- **Content sharing workflows**
  - Facilitates sharing interesting or curated content on social media while driving clicks to a biolink.

- **MCP server endpoint**
  - Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`
  - Single endpoint used across compatible chat or AI clients.

- **Client-agnostic integration**
  - Works with any MCP-capable chat client.
  - Setup is performed in the client by adding the MCP server URL and authenticating.

- **Authentication at configuration time**
  - Authentication occurs when adding the server in the application (exact method depends on the client and Pipedream / gobio.link configuration).

## Integration & Configuration
- **How to add to your app**
  - Select your MCP-compatible chat client and add the static server URL: `https://mcp.pipedream.net/v2`.
  - Authenticate when prompted by the client.
  - Additional setup details are available via the Pipedream Configuration page (not reproduced here).

## Pricing
- Not specified in the provided content.