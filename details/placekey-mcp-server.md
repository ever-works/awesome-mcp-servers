# Placekey MCP Server

An MCP (Model Context Protocol) server that exposes Placekey location capabilities through MCP-compatible tools.

- **Category:** Data Access & Integration – MCP Servers  
- **Provider / Brand:** Placekey (via Pipedream Connect)  
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Description
The Placekey MCP Server provides access to Placekey’s standardized location identifiers and related location data operations through a unified MCP endpoint. It is designed to be added as a remote server in MCP-compatible chat or agent clients.

## Features
- **Standard MCP endpoint**  
  - Single static server URL: `https://mcp.pipedream.net/v2`  
  - Same URL used across all supported MCP clients

- **Client-agnostic integration**  
  - Works with any MCP-compatible chat or agent client  
  - Added via the client’s MCP / tools configuration

- **Authentication at configuration time**  
  - Authentication is handled when adding the server to an application or client (exact method depends on the client and Pipedream/Placekey setup)

- **Configuration resources**  
  - Documentation and setup details available via a central Configuration page on Pipedream

- **Hosted by Pipedream Connect**  
  - Managed as a Pipedream Connect MCP service, including terms and privacy handled by Pipedream

## Integration & Usage
- Use the static MCP URL when configuring tools in compatible clients.  
- Follow the respective client’s guide (via Pipedream’s configuration documentation) to:
  - Add the MCP server URL
  - Complete authentication
  - Enable Placekey-related tools/operations within the client.

## Pricing
No pricing details are provided in the available content. Refer to the Placekey or Pipedream Connect site for current pricing or plan information.