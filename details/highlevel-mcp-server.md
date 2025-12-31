# HighLevel MCP Server

## Overview
HighLevel MCP Server integrates MCP agents with the HighLevel all‑in‑one sales and marketing platform using an API key. It enables applications (such as chat clients) to interact with HighLevel accounts and client data via a standard MCP server endpoint.

- **Category:** Business & Commerce – MCP Servers  
- **Brand:** HighLevel  
- **Integration host:** Pipedream  
- **Authentication method:** HighLevel API key

## Features
- **MCP server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Single endpoint works for all connected HighLevel clients.

- **HighLevel account integration**  
  - Connect a HighLevel account using an API key.  
  - Select a specific client within the connected HighLevel account.  
  - Allows MCP-compatible applications to access and act on HighLevel data (e.g., CRM, funnels, automation) via tools exposed by the server.

- **Client-specific context**  
  - Once authenticated and a client is selected, all MCP interactions can be scoped to that client’s data and configuration in HighLevel.

- **Multi-client support via single URL**  
  - The same MCP server URL can be reused across multiple clients; authentication and client selection determine which HighLevel instance is accessed.

- **Chat client compatibility**  
  - Designed to be added to various chat clients that support MCP servers.  
  - Documentation and client-specific setup instructions are available via the configuration pages.

- **Configuration guidance**  
  - Step-by-step instructions to:  
    - Copy and use the MCP server URL.  
    - Add the server to supported chat clients.  
    - Access the full configuration page for additional setup details.

> Note: The page references “Available tools” but does not list them explicitly; tools are loaded dynamically within Pipedream and may include actions for interacting with CRM, funnels, and automation data.

## Use Cases
- Connect MCP-enabled chat or assistant apps to HighLevel to:  
  - Read and manage CRM data.  
  - Interact with funnels and automations.  
  - Operate on a per-client basis from a single, shared MCP endpoint.

## Pricing
The provided content does not list any pricing details for the HighLevel MCP Server or its plans.