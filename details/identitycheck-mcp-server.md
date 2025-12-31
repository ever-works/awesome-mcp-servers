# IdentityCheck MCP Server

## Overview
IdentityCheck MCP Server is an MCP (Model Context Protocol) server that connects IdentityCheck’s identity verification APIs to AI agents and applications. It enables identity verification to be embedded directly into existing software workflows via a standardized MCP endpoint.

- **Type:** MCP server / integration
- **Category:** Security & Attestation MCP Servers
- **Provider / Brand:** IdentityCheck (via Pipedream Connect)
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features

- **Identity verification integration**  
  - Connects to IdentityCheck’s identity verification APIs.  
  - Allows AI agents to trigger and use identity verification inside their workflows.

- **Standard MCP server interface**  
  - Exposes a static MCP server URL usable by any compatible client.  
  - Works as a plug-in server for MCP-enabled applications (e.g., AI chat clients, agent frameworks).

- **Static endpoint for all clients**  
  - Single, static URL (`https://mcp.pipedream.net/v2`) for all supported clients.  
  - Server-side handling of connections, so client configuration stays minimal.

- **Authentication on client setup**  
  - Authentication is performed when adding the server to your client/application.  
  - Keeps the public server URL static while credentials remain per-user or per-app.

- **Integration with existing software workflows**  
  - Designed to embed identity checks into existing processes (e.g., onboarding flows, compliance steps) via MCP.  
  - Allows AI agents and tools to request or validate identity as part of broader automations.

- **Pipedream Connect platform integration**  
  - Operates on top of Pipedream Connect infrastructure.  
  - Benefits from Pipedream’s configuration and management environment for MCP servers.

- **Client-agnostic setup guidance**  
  - Supports multiple chat / AI clients that understand MCP.  
  - Configuration instructions are available per client type via the referenced configuration page.

## Configuration

- **MCP server URL**:  
  ```
  https://mcp.pipedream.net/v2
  ```
- Add this URL as an MCP server in your MCP-compatible client or application.  
- Authenticate during server addition (exact method depends on the client and Pipedream/IdentityCheck configuration).
- Further details and per-client setup steps are available on the platform’s configuration page.

## Pricing

- No pricing information is provided in the available content.