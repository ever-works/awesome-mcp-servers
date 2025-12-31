# BuiltWith MCP Server

An MCP server that connects MCP-based agents to BuiltWith, enabling programmatic lookup of website technology stacks and profiling data.

---

## Overview
- **Type:** MCP server / integration
- **Category:** Web search MCP servers
- **Provider:** Pipedream
- **Technology Source:** BuiltWith
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

The BuiltWith MCP Server lets agents query BuiltWith data to find out what technologies a given website uses and access related profiling information via the MCP protocol.

---

## Features
- **Technology stack lookup**  
  - Identify what a website is “built with” (frameworks, libraries, services, platforms, etc.).
- **Website profiling data access**  
  - Programmatic access to BuiltWith profiling data for given domains (e.g., technology usage metadata).
- **Static MCP server URL**  
  - Single, static MCP endpoint: `https://mcp.pipedream.net/v2` used for all clients.
- **MCP-based agent integration**  
  - Designed to be added as an MCP server to compatible chat or agent clients.
- **Account-based authentication**  
  - Uses authentication when adding the server to your application (after connecting your account in Pipedream).
- **Multi-client support**  
  - Can be configured with different chat clients; setup instructions are provided per client.
- **Central configuration page**  
  - Configuration and client-specific setup details are available via a dedicated configuration page on Pipedream.

---

## Setup & Configuration
- Connect your Pipedream account and select your BuiltWith client within Pipedream.
- Use the static MCP server URL `https://mcp.pipedream.net/v2` when adding the server to your MCP-compatible app.
- Follow client-specific instructions from the configuration page to complete integration.

---

## Pricing
Pricing information is not provided in the available content. Users should refer to the Pipedream and/or BuiltWith websites for current pricing details.