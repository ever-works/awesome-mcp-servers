# UserVoice MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** UserVoice  
**Source:** https://mcp.pipedream.com/app/uservoice

## Overview
UserVoice MCP Server is an MCP (Model Context Protocol) server that connects applications to UserVoice, enabling tools and agents to work with user feedback collection and management capabilities directly through the MCP interface. It is hosted by Pipedream and exposes a static MCP server URL that can be integrated into compatible chat or agent clients.

## Features
- **MCP-based integration with UserVoice**  
  - Connects MCP-compatible tools and applications to UserVoice.  
  - Enables interaction with user feedback data and related CRM-like workflows via MCP.

- **Static MCP server endpoint**  
  - Single static server URL for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - The same endpoint is used across different chat/agent clients.

- **Per-client authentication**  
  - Authentication occurs when adding the MCP server to an application or chat client.  
  - Works with multiple clients while maintaining secure access to the connected UserVoice account.

- **Configuration flow**  
  - Connect a UserVoice account via the Pipedream UI.  
  - Select the relevant client (chat or agent application) to receive integration instructions.  
  - Option to review full configuration details on a dedicated configuration page.

- **Tool discovery through MCP**  
  - The server exposes “available tools” (actions) for interaction with UserVoice once loading is complete.  
  - Tools appear dynamically in compatible MCP clients as actions and functions.

## Usage
- Copy the MCP server URL (`https://mcp.pipedream.net/v2`).  
- Add it as an MCP server in a supported chat or agent client.  
- Authenticate with the connected UserVoice account when prompted.  
- Use the exposed tools to work with user feedback and related CRM-style data.

## Pricing
No pricing information is provided in the available content.