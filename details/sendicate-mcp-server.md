# Sendicate MCP Server

**Category:** Business & Commerce · MCP Servers  
**Tags:** email-marketing, campaigns, design

## Overview
Sendicate MCP Server is an integration that connects Sendicate—an email marketing app for creating and sending well‑designed email campaigns—to MCP‑compatible clients (such as AI chat clients or tools that support the MCP protocol). It allows those clients to interact with Sendicate via a standardized MCP server endpoint.

- **Product name:** Sendicate MCP Server  
- **Underlying service:** Sendicate (email marketing platform)  
- **Purpose:** Enable MCP clients to work with Sendicate email campaigns and contacts through a shared server endpoint.  
- **Provider infrastructure:** Powered by Pipedream Connect.

## Features
- **Static MCP server endpoint**  
  - Uses a single, static URL for all MCP clients:  
    - `https://mcp.pipedream.net/v2`  
  - The same URL can be reused across different compatible clients.

- **Client‑side authentication**  
  - Authentication occurs when adding the server to your MCP‑compatible application or chat client.  
  - Keeps the server URL generic while credentials and configuration remain client‑specific.

- **Integration with MCP‑compatible chat clients**  
  - Can be added to supported chat or agent clients that understand the MCP protocol.  
  - Setup is initiated from within the client by specifying the server URL and completing authentication.

- **Configuration guidance (external)**  
  - A general configuration page (on Pipedream) explains how to add MCP servers to various clients.  
  - The same configuration approach applies to this Sendicate MCP Server.

- **Hosted / managed by Pipedream**  
  - The MCP server endpoint and connection flow are provided via Pipedream’s infrastructure.  
  - Terms of use and privacy are governed by Pipedream’s policies.

## Usage
- Point your MCP‑compatible client to: `https://mcp.pipedream.net/v2`.
- Complete authentication within your client when prompted.
- Once configured, the client can interact with the Sendicate service through this MCP server (exact operations depend on the client’s capabilities and configuration).

## Pricing
No pricing information is provided in the available content for the Sendicate MCP Server or its usage via Pipedream. Pricing, if any, would need to be checked on Pipedream or Sendicate directly.