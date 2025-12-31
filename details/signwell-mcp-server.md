# SignWell MCP Server

SignWell MCP Server provides MCP-compatible agents with access to SignWell’s electronic signature capabilities, enabling creation and management of e-signature workflows.

## Overview
- **Name:** SignWell MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Use Case:** Integrate legally binding electronic signatures and document signing workflows into MCP-based agents or chat clients.

## Features
- **Electronic Signatures**  
  - Supports legally binding e-signatures.  
  - Designed for faster document signing processes.

- **E-Sign Document Workflows**  
  - Send documents for electronic signature.  
  - Track the status of e-sign documents.  
  - Manage active and completed e-signature documents and workflows.

- **MCP Integration**  
  - Exposes SignWell functionality via the Model Context Protocol (MCP).  
  - Allows MCP-compatible agents and applications to access SignWell workflows.  
  - Uses a static MCP server URL for all clients:  
    - `https://mcp.pipedream.net/v2`

- **Client-Agnostic Server URL**  
  - Single, static server endpoint that works across supported MCP clients.  
  - Authentication is handled when adding the server into the client/application.

## Configuration
- Add the MCP server to a supported chat client or MCP-compatible application using:  
  - **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- Additional configuration instructions are available on the provider’s configuration documentation (referenced as the “Configuration page”).

## Tags
- e-signature  
- document-workflows

## Pricing
- No pricing information is provided in the available content.