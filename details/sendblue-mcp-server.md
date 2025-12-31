# Sendblue MCP Server

**Category:** Messaging MCP Servers  
**Brand:** sendblue  
**Website:** https://mcp.pipedream.com/app/sendblue

## Overview
Sendblue MCP Server is an MCP-compatible integration that exposes Sendblue’s scalable iMessage API to MCP tools and agents. It allows applications that support the Model Context Protocol (MCP) to send and manage iMessage communication through a unified server endpoint.

## Features
- **MCP-compatible iMessage access**: Provides a server interface that lets MCP-enabled clients use Sendblue’s iMessage API.
- **Single static MCP endpoint**: Uses a fixed server URL (`https://mcp.pipedream.net/v2`) that works across all supported MCP clients.
- **Account-based authentication**: Authentication occurs when adding the server to an MCP-compatible application, tied to a configured Sendblue account.
- **Client-agnostic setup flow**: Supports multiple chat clients; users select their client and follow tailored setup steps.
- **Configuration via web UI**: A configuration page guides connecting a Sendblue account and adding the MCP server to applications.
- **Scalable messaging**: Designed for use with Sendblue’s “Simple iMessage API ready for scale,” suitable for higher-volume or programmatic messaging scenarios.

## Configuration
- **MCP server URL**: `https://mcp.pipedream.net/v2` (static, shared across clients).
- **Setup steps**:
  - Connect a Sendblue account via the Pipedream-based configuration interface.
  - Copy the MCP server URL.
  - Add the server URL to the desired MCP-compatible chat client or agent following that client’s instructions.
  - Authenticate when prompted in the client.

## Pricing
No pricing details are provided in the available content. Users should refer to the Sendblue or Pipedream websites for current pricing information related to the iMessage API and MCP server usage.
