# SignerX MCP Server

## Overview
SignerX MCP Server is a Model Context Protocol (MCP) server that connects AI agents to SignerX’s digital document signing capabilities. It enables applications and chat-based AI clients to interact with SignerX for document-related workflows through a unified MCP endpoint.

- **Category:** Business & Commerce – MCP Servers
- **Use cases:** E-signatures, document automation, integrating signing flows into AI/chat clients.

## Features
- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Can be added as a server to compatible chat or AI applications.

- **SignerX integration**  
  - Designed to work with SignerX’s digital signature and document signing features.  
  - Allows AI agents to initiate and work with document signing workflows via MCP (details of individual tools/actions are dynamically loaded in the interface).

- **Account-based configuration**  
  - Requires connecting a SignerX account before use.  
  - Once authenticated, the same MCP URL can be used across different clients.

- **Client-agnostic setup**  
  - The static MCP URL works with multiple compatible clients.  
  - Documentation/links are provided in the UI to add the server to specific chat clients or to view the full configuration page.

## Technical Details
- **Protocol:** Model Context Protocol (MCP)
- **Endpoint:** `https://mcp.pipedream.net/v2`
- **Hosting/Provider:** Pipedream

## Pricing
The provided content does not list any pricing or plan information for the SignerX MCP Server.