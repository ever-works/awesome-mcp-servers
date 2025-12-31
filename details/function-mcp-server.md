# Function MCP Server

Run Python compute workloads via a simple `predict` function interface, accessible as an MCP Server.

- **Category:** Code Execution & Automation – MCP Servers  
- **Tags:** python, serverless, code-execution
- **Provider:** Pipedream (Pipedream Connect)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Overview
Function MCP Server exposes a static MCP endpoint that lets clients run Python compute workloads using a single `predict` function interface, enabling serverless-style Python execution from compatible MCP-enabled chat or application clients.

## Features
- **Python compute workloads**: Execute Python code as remote compute jobs through MCP.  
- **Simple `predict` interface**: Interact with Python execution using a single, standardized function (`predict`) rather than managing multiple endpoints.  
- **Serverless-style execution**: Offload compute to a managed MCP server instead of running your own infrastructure.  
- **Static MCP endpoint**: Use one static URL (`https://mcp.pipedream.net/v2`) for all supported clients.  
- **Client-agnostic**: Designed to work with any MCP-compatible chat client or application.  
- **Authentication at client setup**: Auth is handled when adding the server to your client or app, not by changing the server URL.  
- **Central configuration docs**: Full configuration details available via a dedicated configuration page (referenced from the product page).

## Integration & Usage
- Add the static MCP server URL to your MCP-enabled client or application.  
- Authenticate during client/server setup as instructed by your specific client.  
- Use the exposed `predict` function to send Python workloads for remote execution.

## Pricing
- Not specified in the provided content.
