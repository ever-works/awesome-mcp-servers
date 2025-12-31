# IBM Cloud Speech to Text MCP Server

## Overview
The IBM Cloud Speech to Text MCP Server is an MCP-compatible service that exposes IBM Cloud’s Speech to Text capabilities to MCP-based agents and tools. It enables applications and chat clients that support the MCP protocol to perform speech recognition and transcription using a unified MCP server endpoint.

- **Category:** Media Processing MCP Servers  
- **Tags:** speech-to-text, transcription, AI integration  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible speech recognition** – Provides access to IBM Cloud Speech to Text through the Model Context Protocol, allowing integration with MCP-based agents and tools.
- **Unified static server URL** – Uses a single static MCP server endpoint (`https://mcp.pipedream.net/v2`) for all supported clients.
- **Authentication at client setup** – Authentication is handled when adding the MCP server to your application or chat client.
- **Multi-client support** – Can be added to different chat clients or applications that understand MCP, using the same server URL.
- **Tool-based interaction** – Exposes speech-to-text and transcription functionality as MCP tools that can be invoked by compatible clients (listed as “available tools” in the interface).
- **Configuration guidance** – Includes guidance via a configuration page on how to connect an IBM Cloud Speech to Text account and select a client.

## Integration
- Connect an IBM Cloud Speech to Text account via the Pipedream interface.
- Copy and use the static MCP server URL in any MCP-compatible client.
- Configure the client according to the instructions provided per chat client or via the general configuration page.

## Pricing
The provided content does not include any pricing or plan details for the IBM Cloud Speech to Text MCP Server.