# Upstash Redis MCP Server

Upstash Redis database as a service, exposed via the Model Context Protocol (MCP).

## Overview
- **Name:** Upstash Redis MCP Server  
- **Provider / Brand:** Upstash (via Pipedream Connect)  
- **Category:** Database / Messaging MCP Server  
- **Type:** MCP server for connecting applications to Upstash’s serverless Redis database as a service  
- **Protocol:** Model Context Protocol (MCP)

## Features
- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL that can be used with any compatible client:  
    - `https://mcp.pipedream.net/v2`
- **Client-agnostic usage**  
  - Designed to work with multiple MCP-capable chat clients and applications.  
  - Can be added to different clients through their MCP configuration.
- **Authentication at configuration time**  
  - The static URL is the same for all clients; authentication is handled when you add/configure the server in your application.
- **Integration via configuration page**  
  - Detailed setup and configuration steps are available through a dedicated configuration page (referenced as “Configuration page” on the site).
- **Serverless Redis backend**  
  - Connects to Upstash’s serverless Redis database as a service, enabling key-value data operations through MCP.

## Usage
- Use the static MCP server URL in your MCP-aware client:  
  - `https://mcp.pipedream.net/v2`
- Configure authentication and any required parameters in your client’s MCP configuration interface or configuration file.

## Pricing
- No pricing information is provided in the available content.

## Tags
- redis  
- key-value  
- cloud  
- mcp  
- database  
- serverless