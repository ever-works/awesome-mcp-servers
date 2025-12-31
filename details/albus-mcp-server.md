# Albus MCP Server

## Overview
Albus MCP Server is an MCP (Model Context Protocol) server that integrates the Albus AI assistant into LLM-powered applications. It focuses on AI-powered Slack search and web assistant capabilities, making Albus tools accessible via a standard MCP endpoint.

- **Category:** AI Integration – MCP Servers  
- **Brand:** Albus  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server**  
  - Exposes Albus functionality through the Model Context Protocol.  
  - Uses a static MCP server URL that works across clients.

- **AI-powered Slack search**  
  - Provides AI-driven search capabilities over Slack content (as exposed via Albus) to connected LLM agents.  

- **Web assistant capabilities**  
  - Enables LLM agents to use Albus as a web assistant (e.g., retrieving or reasoning over web-accessible information through Albus’s tools).

- **Client-agnostic configuration**  
  - Single static URL (`https://mcp.pipedream.net/v2`) used for all compatible clients.  
  - Authentication handled when adding the server to an application.  
  - Documentation available for different chat/LLM clients via a configuration page.

- **Account-based setup**  
  - Connects to a user’s Albus/Pipedream account.  
  - Allows selecting the appropriate client and configuring the server for that environment.

## Integration & Usage
- Add the MCP server URL to any MCP-compatible chat or LLM client.  
- Authenticate during client setup to grant access to Albus tools.  
- Once configured, LLM agents can call the available Albus tools (Slack search, web assistant functions) through the MCP interface.

## Pricing
No pricing information is provided in the available content.