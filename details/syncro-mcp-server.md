# Syncro MCP Server

## Overview
The Syncro MCP Server exposes Syncro’s MSP platform capabilities—PSA, RMM, and remote access—through the Model Context Protocol (MCP). It allows MCP-compatible applications (such as chat-based clients or AI assistants) to connect to a Syncro account and operate on behalf of a selected client.

- **Product type:** MCP server integration
- **Category:** Business & Commerce MCP Servers
- **Use case:** Managed Service Providers (MSPs) needing PSA, RMM, and remote access functions accessible via MCP-aware tools.

## Features
- **PSA (Professional Services Automation) integration**  
  Access Syncro’s PSA capabilities via MCP so that compatible applications can interact with tickets, workflows, and other business operations (as supported by Syncro’s PSA APIs and tools exposed through this MCP server).

- **RMM (Remote Monitoring & Management) integration**  
  Exposes Syncro’s RMM functionality through MCP to enable management and monitoring of client devices and environments from MCP-aware clients.

- **Remote access capabilities**  
  Makes Syncro’s remote access features available through the MCP interface so users can trigger or manage remote sessions from integrated applications (subject to Syncro’s feature set and permissions).

- **Single, static MCP server URL**  
  - MCP endpoint: `https://mcp.pipedream.net/v2`  
  - The same URL works for all clients; authentication and client selection occur when adding and configuring the server in the application.

- **Per-client configuration flow**  
  - Connect a Syncro account.  
  - Select the relevant client within Syncro.  
  - Use the connected context in MCP-compatible applications.

- **Works with multiple chat / MCP clients**  
  The server can be added to various MCP-aware chat clients or applications; each client follows its own setup flow using the same static MCP URL.

- **Hosted by Pipedream**  
  The MCP server is provided and hosted via Pipedream’s platform, utilizing their infrastructure and configuration model.

## Configuration & Usage
- Copy and use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the MCP server to a supported chat client or MCP-compatible application.
- Authenticate with Syncro when prompted and select the desired client.
- Once configured, the application can call the tools and actions exposed by the Syncro MCP Server (PSA, RMM, remote access), as supported by the integration.

## Pricing
The provided content does not specify any pricing or plans for the Syncro MCP Server. Pricing details, if any, would need to be obtained from Syncro or Pipedream directly.