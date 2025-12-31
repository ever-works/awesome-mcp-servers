# GoSquared MCP Server

## Overview
The GoSquared MCP Server is an MCP (Model Context Protocol) server integration that connects MCP-compatible applications to the GoSquared growth platform. It enables AI or chat-based clients to interact with GoSquared’s sales and marketing capabilities and visitor analytics via a standardized MCP endpoint.

- **Category:** Business & Commerce MCP Servers  
- **Vendor / Brand:** GoSquared (via Pipedream)  
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **MCP server integration for GoSquared**  
  - Exposes GoSquared functionality through the MCP protocol so compatible apps can access GoSquared data and actions.

- **Single static server URL**  
  - Uses a fixed MCP server URL (`https://mcp.pipedream.net/v2`) that works for every GoSquared client.  
  - Simplifies configuration by not requiring per-client endpoint changes.

- **Authentication at application level**  
  - Authentication is performed when adding the MCP server to your client / application instead of using a different URL per account.

- **Client-agnostic setup**  
  - Can be added to various MCP-compatible chat clients or applications (e.g., AI assistants) using the same configuration endpoint.

- **Configuration guidance**  
  - Provides instructions to:  
    - Connect a GoSquared account via Pipedream.  
    - Select the associated client within the Pipedream UI.  
    - Copy and use the MCP server URL.  
    - Access a full configuration page for detailed setup steps.

- **Tooling / actions exposure (via MCP)**  
  - Designed to expose “tools” or actions related to GoSquared (shown as “Available tools” in the interface).  
  - These tools allow an MCP client to call GoSquared-related operations (e.g., around sales, marketing collaboration, or visitor analytics), though specific tools are not detailed in the provided content.

## Use Cases
- Integrate GoSquared visitor analytics and growth platform features into MCP-based AI/chat applications.  
- Enable sales and marketing teams using MCP-enabled tools to work with GoSquared data and actions from within their existing workflows.

## Pricing
- The provided content does not include any pricing information for the GoSquared MCP Server or associated GoSquared / Pipedream plans.
