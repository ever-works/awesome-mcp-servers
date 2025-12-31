# CIRCL Hash Lookup MCP Server

## Overview
The CIRCL Hash Lookup MCP Server exposes CIRCL’s public hash lookup API via the Model Context Protocol (MCP). It enables MCP-compatible tools and chat clients to query file hash values against known file databases for security and digital forensics use cases.

- **Category:** Security Attestation MCP Servers  
- **Brand:** CIRCL  
- **Slug:** `circl-hash-lookup-mcp-server`  
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **Public hash lookup API integration**  
  - Interfaces with CIRCL’s public hash lookup service.  
  - Allows lookup of hash values against a known database of files.

- **Security and forensics use cases**  
  - Supports threat intelligence workflows by checking if a file hash is known in CIRCL datasets.  
  - Useful for incident response and digital forensics to quickly assess file reputation.

- **MCP-compatible server**  
  - Exposes CIRCL hash lookup as an MCP server for use in MCP-enabled tools and chat clients.  
  - Uses a static MCP server URL: `https://mcp.pipedream.net/v2`.

- **Client-agnostic configuration**  
  - Same MCP server URL works across different MCP clients.  
  - Authentication is handled when adding the server to the client/application.

## Integration & Usage
- Add `https://mcp.pipedream.net/v2` as an MCP server in your compatible chat client or tool.  
- Configure authentication within your client when prompted.  
- Use available MCP tools (defined by the client integration) to submit file hashes and retrieve lookup results from CIRCL’s database.

## Pricing
Pricing information is not specified in the provided content.