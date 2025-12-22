# HubSpot MCP Server

## Overview
HubSpot MCP Server is a Model Context Protocol (MCP) server that connects to HubSpot CRM, allowing AI assistants and LLM-based tools to work with HubSpot data using natural language. It supports managing HubSpot contacts and companies directly from within an LLM chat.

- **Repository:** https://github.com/buryhuang/mcp-hubspot  
- **Docker image:** https://hub.docker.com/r/buryhuang/mcp-hubspot  
- **License:** MIT  
- **Brand:** HubSpot  
- **Category:** mcp-server-directories-lists

## Features
- **HubSpot CRM integration**  
  - Connects directly to HubSpot CRM APIs.  
  - Enables interaction with HubSpot CRM data from AI assistants and LLM tools.

- **Natural language CRM operations**  
  - Manage HubSpot contacts via natural language prompts.  
  - Manage HubSpot companies via natural language prompts.  
  - Create new CRM records (e.g., contacts, companies) from within an LLM chat.  
  - Retrieve existing CRM records from within an LLM chat.

- **Performance and scalability helpers**  
  - Built-in vector storage to support semantic operations over HubSpot data.  
  - Caching mechanisms to:  
    - Mitigate HubSpot API limitations.  
    - Improve response times for repeated or similar queries.

- **Deployment & packaging**  
  - Published Docker image available on Docker Hub (`buryhuang/mcp-hubspot`).  
  - Source available as an MCP server implementation in this GitHub repository.

## Pricing
- **Open-source (MIT License)**  
  - Free to use, modify, and self-host under the terms of the MIT license.
