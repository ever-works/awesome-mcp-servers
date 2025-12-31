# Find-A-Domain MCP Server

**Brand:** find-a-domain  
**Category:** Web Search MCP Servers  
**Website / Docs:** https://findadomain.dev/mcp  
**MCP Endpoint:** https://api.findadomain.dev/mcp

Tools for programmatic domain name search and discovery via an MCP-compatible server.

---

## Overview
The Find-A-Domain MCP Server exposes domain lookup utilities over the Model Context Protocol (MCP), allowing compatible clients (such as Docker Desktop MCP integrations) to search for and inspect domain names and available top-level domains.

---

## Features

### MCP Integration
- MCP-based server accessible at `https://api.findadomain.dev/mcp`.
- Can be added directly to Docker Desktop as an MCP server (requires Docker Desktop **version 4.43 or later** for automatic configuration).

### Available Tools
The server currently exposes **2 tools**:

1. **Check domain availability for a specific TLD**
   - Input: domain name and target TLD.
   - Output: whether the domain is available under that TLD.
   - Use case: validate if a specific domain (e.g., `example.dev`) is free to register.

2. **List all available top-level domains (TLDs)**
   - Returns a list of supported/available TLDs that can be queried.
   - Use case: discover which TLDs you can search or register against.

### Documentation
- Detailed MCP server and tool documentation is available at: https://findadomain.dev/mcp

---

## Pricing
No pricing information is provided in the source content.

---

## Tags
- domain  
- search  
- api-integration