# Salesflare MCP Server

## Overview
Salesflare MCP Server is an MCP (Model Context Protocol) server integration that connects MCP-compatible applications to Salesflare, an intelligent, zero-input CRM designed for startups and small businesses. It exposes Salesflare’s CRM and sales pipeline automation capabilities as tools that can be invoked within MCP-based workflows.

## Key Details
- **Name:** Salesflare MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Primary Function:** MCP integration with Salesflare CRM and sales pipeline automation  
- **Provider / Platform:** Pipedream  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server endpoint**  
  - Provides a static MCP server URL (`https://mcp.pipedream.net/v2`) that can be added to any MCP-capable client.
  - Authentication is handled when adding the server to an MCP-based application.

- **Salesflare CRM integration**  
  - Connects to a Salesflare account to expose CRM data and operations to MCP tools and workflows.  
  - Targets startups and small businesses using Salesflare as their primary CRM.

- **Sales pipeline automation access**  
  - Integrates Salesflare’s “zero-input” sales pipeline capabilities, allowing workflows to leverage automated data capture and pipeline management via MCP tools.

- **Client-agnostic configuration**  
  - Works with multiple MCP-enabled chat or agent clients; users can select their client and follow tailored setup instructions.  
  - Central configuration documentation is available via the Pipedream configuration page (for steps specific to different clients).

- **Tool exposure within MCP**  
  - Makes Salesflare-related actions and tools available under “Available tools” in compatible MCP clients (exact tools are dynamically loaded by the platform).

## Setup & Usage
1. **Copy MCP Server URL:** Use `https://mcp.pipedream.net/v2` as the server endpoint.  
2. **Add to MCP Client:** Add the server URL to your chosen MCP-compatible app or chat client.  
3. **Authenticate:** Connect your Salesflare account when prompted to enable CRM and pipeline tools.  
4. **Use Tools:** Invoke the Salesflare tools exposed by the MCP server within your workflows or chat environment.

## Pricing
Pricing details for the Salesflare MCP Server are not provided in the available content. Users should refer to Pipedream and Salesflare pricing pages for any associated costs.