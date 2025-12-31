# Esendex MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Pipedream  
**Website:** https://mcp.pipedream.com/app/esendex

## Description
Esendex MCP Server is an integration on Pipedream that exposes Esendex’s SMS, voice, web, and multichannel business communication capabilities as tools within MCP-compatible workflows and applications.

## Features
- **MCP server integration**: Provides an MCP-compliant server endpoint for integrating Esendex into compatible chat clients and developer tools.
- **Static MCP server URL**: Uses a single static endpoint for all clients:
  - `https://mcp.pipedream.net/v2`
- **Account-based authentication**: Authentication occurs when adding the MCP server to an application, after connecting an Esendex account in Pipedream.
- **Esendex configuration in Pipedream**:
  - Connect an Esendex account within Pipedream.
  - Select the relevant client (chat client or app) to start using Esendex tools.
- **Multichannel communication support**: Designed to work with Esendex’s business communication channels, including:
  - SMS
  - Voice
  - Web-based communication
  - Other multichannel messaging options supported by Esendex
- **Tool-based workflow integration**: Exposes Esendex functionality as “tools” that can be invoked from clients and workflows (tool list is dynamically loaded in the UI).
- **Client-agnostic usage**: The same MCP server URL can be added to different MCP-compatible chat clients, with configuration guidance per client.
- **Central configuration reference**: Additional setup and configuration options are available via a dedicated configuration page on Pipedream.

## Technical Details
- **MCP server endpoint:** `https://mcp.pipedream.net/v2`  
- **Integration context:** Runs within the Pipedream platform and relies on a connected Esendex account.

## Pricing
No pricing information is provided in the available content. Refer to the Pipedream website or Esendex MCP Server app page for current pricing details.