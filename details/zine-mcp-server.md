# Zine MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** Zine  
**Website:** https://www.zine.ai  
**Source URL:** https://www.zine.ai/blog/mcp-turns-knowledge-into-action

## Overview
Zine MCP Server is a memory-focused Model Context Protocol (MCP) server that exposes Zine’s long-term memory and organizational knowledge capabilities to MCP-compatible AI clients via a remote HTTP endpoint and OAuth 2.1. It lets tools like Claude Desktop, Cursor, and other MCP clients access and search your internal knowledge base in a standardized way.

## Features
- **MCP-Compatible Server**  
  - Implements the Model Context Protocol (MCP) as an MCP server.  
  - Exposes organizational knowledge as structured tools/data sources to any MCP client.

- **Remote Streamable HTTP Endpoint**  
  - Accessible at `https://www.zine.ai/mcp`.  
  - Designed to be consumed remotely by AI tools rather than running locally.

- **Long-Term Memory & Knowledge Access**  
  - Provides access to Zine’s long-term memory layer and knowledge base.  
  - Allows AI agents to pull in relevant organizational context (documents, discussions, internal references) during a session.

- **OAuth 2.1 Integration**  
  - Uses OAuth 2.1 for secure authentication and authorization between MCP clients and the Zine server.

- **Works with Multiple MCP Clients**  
  - Can be used by MCP-compatible clients such as Cursor, Claude Desktop, Goose, and others that implement the MCP standard.  
  - “Write once, use everywhere” model: the same server integration works across different AI tools.

- **Part of a Dual Architecture (Server + Client)**  
  - Zine functions as both an MCP server (exposed at `https://www.zine.ai/mcp`) and an MCP client internally.  
  - The server makes Zine’s knowledge accessible to external tools; the client side lets Zine connect to additional data sources and tools via MCP.

- **Standardized Knowledge Access**  
  - Uses the MCP standard so any compliant client can query, search, or otherwise interact with the knowledge base without custom, one-off integrations.  
  - Helps avoid vendor lock-in by separating the knowledge server (Zine) from the specific AI client.

## Use Cases
- Enable AI coding tools (e.g., Cursor) to reference internal APIs, style guides, and historical code reviews directly from Zine.  
- Allow knowledge workers using Claude Desktop or other MCP clients to search internal documents, research, and discussions stored in Zine without manual copy-paste.

## Pricing
No pricing information is provided in the available content.