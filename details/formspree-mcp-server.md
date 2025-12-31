# Formspree MCP Server

**Category:** Business & Commerce · MCP Servers  
**Slug:** formspree-mcp-server  
**Brand:** Formspree

## Description
Formspree MCP Server is an MCP-compatible server that connects AI tools and MCP clients to Formspree’s online form backend. It allows applications and agents to programmatically interact with Formspree form endpoints and submissions via a standardized MCP interface.

MCP access is provided via Pipedream Connect using a static server URL:

```text
https://mcp.pipedream.net/v2
```

## Features
- **MCP-compatible server**: Exposes Formspree functionality over the Model Context Protocol for easy integration into AI tools and chat-based clients.
- **Static server URL**: Uses a single, fixed MCP server endpoint (`https://mcp.pipedream.net/v2`) that works across supported clients.
- **Formspree backend integration**: Connects to Formspree’s online form service to work with form endpoints and submissions (creation, handling, and management of form data, as supported by Formspree and the MCP implementation).
- **Programmatic access for AI tools**: Enables AI agents and clients to interact with form submissions and form endpoints programmatically (e.g., reading or sending data to Formspree endpoints), subject to the capabilities exposed by the MCP tools.
- **Client-agnostic setup**: Designed to be added to various MCP-capable chat clients and applications; authentication is handled when adding the server to each client.
- **Pipedream Connect integration**: Hosted and powered by Pipedream Connect infrastructure for MCP connectivity.

## Configuration
- **Server URL**: `https://mcp.pipedream.net/v2`  
- **Authentication**: Performed when adding the MCP server to a compatible application or chat client.  
- Additional setup instructions and client-specific steps are available on the provider’s configuration page (not included in the provided content).

## Pricing
The provided content does not include any pricing information for Formspree MCP Server or associated services.