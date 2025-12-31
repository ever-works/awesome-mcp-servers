# Visitor Queue MCP Server

## Overview
Visitor Queue MCP Server is an MCP-compatible integration for Visitor Queue, a B2B lead generation platform that identifies companies visiting your website along with associated contact and user data. It allows MCP-enabled clients to work with Visitor Queue’s website visitor and lead data through a standardized MCP server endpoint.

- **Category:** Business & Commerce MCP Servers  
- **Use cases:** B2B lead generation, website visitor identification, sales prospecting, website analytics enrichment
- **MCP server URL:** `https://mcp.pipedream.net/v2`

## Features
- **B2B visitor identification**  
  - Identifies businesses that visit your website.  
  - Provides company name and related firmographic information (as supported by Visitor Queue).

- **Lead data access**  
  - Exposes contact details associated with identified companies (e.g., decision-makers or relevant contacts, as available in Visitor Queue).  
  - Surfaces user / visitor data tied to those companies for lead qualification and follow-up.

- **Website analytics enrichment**  
  - Enhances basic web analytics with identifiable B2B visitor information.  
  - Supports using visitor data in downstream workflows like sales outreach or account-based marketing when used in MCP environments.

- **MCP integration**  
  - Provides a single static MCP server URL (`https://mcp.pipedream.net/v2`) for all clients.  
  - Authentication is handled when adding the server to your MCP-compatible application.  
  - Usable across different chat clients and tools that support the Model Context Protocol.

## Setup & Integration
- Use the static MCP server URL `https://mcp.pipedream.net/v2` when configuring an MCP server in your client.  
- Authenticate within your client’s MCP configuration flow (method depends on the client).  
- Refer to your MCP client’s configuration or Pipedream’s configuration documentation for detailed setup steps.

## Pricing
- The provided content does not specify pricing or plans for the Visitor Queue MCP Server or the underlying Visitor Queue service.