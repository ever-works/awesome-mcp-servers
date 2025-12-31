# Daffy MCP Server

## Overview
Daffy MCP Server is an MCP (Model Context Protocol) server integration that lets MCP-based agents interact with Daffy’s charitable giving platform. It enables agents and compatible chat clients to support charitable contributions and donations through Daffy.

## Key Details
- **Name:** Daffy MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Tags:** donations, nonprofit, payments  
- **Provider / Brand:** Daffy (delivered via Pipedream Connect)  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP Integration**  
  - Provides an MCP server endpoint that can be added to any compatible MCP client.  
  - Uses a single static URL (`https://mcp.pipedream.net/v2`) for all clients, with authentication handled during client setup.

- **Charitable Giving Platform Access**  
  - Enables MCP-based agents to interact with Daffy’s charitable giving platform.  
  - Supports workflows around contributions and donations to U.S. charities.

- **Supported Contribution Types**  
  - Contribute cash.  
  - Contribute stock or ETFs.  
  - Contribute cryptocurrency (crypto).

- **Tax-Advantaged Growth (Platform Capability)**  
  - Contributions on Daffy’s platform can grow tax-free before being donated (capability of the underlying Daffy platform that agents integrate with via MCP).

- **Broad Charity Coverage**  
  - Donate to nearly any U.S. charity supported by Daffy.

- **Client-Agnostic Setup**  
  - Single static server URL works across different MCP-compatible chat clients.  
  - Authentication occurs when adding the server to each application/client.

## Configuration
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Setup:** Add this URL as an MCP server in your MCP-compatible chat client and complete its authentication flow.  
- **Additional Docs:** Full configuration details are available on the provider’s configuration page (referenced as “Configuration page” in the original source).

## Pricing
The provided content does not include any pricing or plan information for the Daffy MCP Server or the underlying Daffy service.