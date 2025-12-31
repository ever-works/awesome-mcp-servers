# Nimble MCP Server

AI-powered CRM MCP server for integrating Nimble’s relationship management features into compatible chat and MCP-enabled applications.

---

## Overview
- **Name:** Nimble MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Use Case:** Connect an AI-powered CRM (Nimble) to MCP-compatible chat clients and applications to support sales and digital marketing relationship management.

---

## Features
- **MCP-compatible CRM server**  
  - Exposes Nimble (AI-powered CRM) as an MCP server endpoint for use in MCP-enabled apps and chat clients.

- **Static server URL**  
  - Single static URL for all clients: `https://mcp.pipedream.net/v2`  
  - Same endpoint used across different chat clients and tools.

- **Account-based configuration**  
  - Connect a Nimble account via Pipedream’s configuration flow.  
  - Select the appropriate client or environment after connecting your account.

- **Per-app authentication**  
  - Authentication occurs when adding the server to each application or chat client.  
  - Supports secure access to CRM data from multiple clients using the same base URL.

- **Chat client integration**  
  - Documentation and guided setup for adding the Nimble MCP Server to supported chat clients.  
  - Links to a full configuration page for more detailed setup steps.

- **Tooling exposure (actions)**  
  - Designed to load and expose Nimble-related “tools” or actions once configured (e.g., CRM operations within the MCP framework).  
  - Tools are discovered dynamically after account connection (shown as “Loading actions… / Loading available tools…” in the interface).

---

## Pricing
Pricing information is not provided in the available content.

---

## Technical Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Hosting/Provider:** Pipedream  
- **Integration Model:** Add as an MCP server to compatible chat clients and applications, then authenticate with a Nimble account.