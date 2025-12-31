# Cloudinary Asset Management MCP Server

**Brand:** Cloudinary  
**Category:** Media Processing MCP Servers  
**Website:** https://cloudinary.com/documentation/asset_management  
**Source URL (MCP SSE endpoint):** https://asset-management.mcp.cloudinary.com/sse

## Overview
The Cloudinary Asset Management MCP Server exposes Cloudinary’s media and digital asset management APIs to MCP-compatible clients via an OAuth 2.1-secured server-sent events (SSE) endpoint. It allows LLM tools, editors, and other MCP-aware applications to browse, search, upload, and work with Cloudinary assets programmatically.

## Features
- **MCP-compatible media access**  
  - MCP server endpoint at `https://asset-management.mcp.cloudinary.com/sse`  
  - Designed to plug into MCP-aware clients and LLM tools (Beta per Cloudinary docs section)

- **OAuth 2.1 authentication**  
  - Uses OAuth 2.1 to authorize access to Cloudinary accounts and assets  
  - Provides secure, scoped access to media operations from MCP clients

- **Cloudinary Asset & DAM API integration**  
  - Connects to Cloudinary’s Assets (DAM) APIs  
  - Supports programmatic access to assets stored in Cloudinary Media Library  
  - Leverages existing Cloudinary account, configuration, and permissions

- **Media asset management operations**  
  *(Inferred from Cloudinary’s asset management capabilities and MCP positioning)*  
  - Browse and list assets from Cloudinary repositories  
  - Search for assets using Cloudinary’s asset metadata and query capabilities  
  - Upload new media assets into Cloudinary from MCP clients  
  - Reference assets (e.g., retrieve URLs or identifiers) for use in code, content, or tools

- **Ecosystem and tooling alignment**  
  - Part of the “MCP servers and LLM tools (Beta)” offering in Cloudinary’s documentation  
  - Complements other developer tools such as the Cloudinary VS Code Extension and SDKs

## Use Cases
- Integrating Cloudinary asset browsing and search into MCP-enabled IDEs, editors, or chat-based tools.
- Allowing LLM tools to fetch, reference, or upload media assets from/to a Cloudinary account.
- Building workflows where media asset management is handled directly via MCP instead of separate dashboards.

## Pricing
The documentation snippet provided does not list specific pricing for the **Cloudinary Asset Management MCP Server** itself.

Cloudinary has a general pricing page for its platform and APIs:  
**Cloudinary Pricing:** https://cloudinary.com/pricing  

From the available content, it cannot be determined whether the MCP server has separate pricing or is included within existing Cloudinary plans.