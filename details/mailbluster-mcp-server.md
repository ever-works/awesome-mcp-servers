# Mailbluster MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Mailbluster  
**Slug:** mailbluster-mcp-server

## Description
Mailbluster MCP Server is an MCP (Model Context Protocol) integration that exposes Mailbluster’s Amazon SES–based email marketing capabilities to MCP-compatible applications. It allows apps and chat clients to interact with Mailbluster for email marketing use cases using a standardized MCP server endpoint.

## Features
- **MCP-based integration**: Provides an MCP Server interface so MCP-compatible clients can access Mailbluster features.  
- **Static server endpoint**: Uses a single static MCP server URL for all clients:  
  - `https://mcp.pipedream.net/v2`  
- **Per-client authentication**: Authentication is handled when adding the server to each application or chat client (credentials are not embedded in the static URL).  
- **Amazon SES–backed email marketing**: Integrates with Mailbluster’s email marketing platform, which is built on Amazon SES for sending campaigns.  
- **Multi-client compatibility**: Can be added to various MCP-enabled chat clients and applications using the same server URL.  
- **Configuration documentation**: Supported by a configuration guide via Pipedream’s configuration page to help with setup.

*(The underlying Mailbluster-specific operations exposed via this MCP server are not detailed in the provided content beyond general email marketing via Amazon SES.)*

## Integration & Usage
- **MCP Server URL**: `https://mcp.pipedream.net/v2` (static for all clients).  
- **Setup flow**:
  - Add the server URL to an MCP-compatible chat client or application.  
  - Authenticate within the client during server setup.  
  - Use the Mailbluster MCP Server within the client to access Mailbluster’s email marketing capabilities.

## Pricing
The provided content does not include any pricing or plan information for the Mailbluster MCP Server or Mailbluster itself.