# imgix MCP Server

## Overview
The imgix MCP Server is an MCP (Model Context Protocol) server endpoint that exposes imgix visual media processing and optimization capabilities for use inside compatible applications and workflows, including Pipedream-based setups.

- **Category:** media-processing-mcp-servers  
- **Provider / Brand:** Pipedream  
- **Primary Use Case:** Integrate imgix image/media processing into chat clients or other MCP-compatible tools via a single static MCP server URL.

## Features
- **Static MCP server endpoint**  
  - Uses a single static URL for all supported MCP clients:  
    - `https://mcp.pipedream.net/v2`
  - Same URL works across different chat clients and applications.

- **Account-based configuration**  
  - Supports connecting and configuring an imgix account before use.  
  - Provides a guided “Configure imgix” flow to connect your account and client.

- **Client-agnostic integration**  
  - Designed for use with multiple chat clients / MCP-capable applications.  
  - Offers per-client setup instructions after you select your chat client.  
  - Can be added to various apps that support MCP by referencing the static server URL.

- **Tool/action loading via MCP**  
  - Exposes imgix-related tools and actions over MCP (listed in the UI as “Available tools”).  
  - Tools are dynamically loaded by compatible MCP clients, enabling image/media transformation and optimization workflows.

- **Authentication at client level**  
  - Authentication occurs when adding the server to an application, rather than per-URL.  
  - Allows secure use of imgix processing features within MCP clients.

- **Integration in Pipedream ecosystem**  
  - Built and hosted by Pipedream, enabling use alongside other Pipedream integrations and workflows.

## Pricing
Pricing information for the imgix MCP Server is not provided in the available content.