# Dandelion MCP Server

Semantic Text Analytics as a Service

## Overview
The Dandelion MCP Server integrates the Dandelion semantic text analytics API with the Model Context Protocol (MCP), enabling NLP and entity extraction capabilities for MCP-compatible clients via a static MCP endpoint.

- **Type:** MCP server integration
- **Category:** AI Integration – MCP Servers
- **Provider / Brand:** dandelion-api (via Pipedream Connect)
- **MCP Endpoint URL:** `https://mcp.pipedream.net/v2`

## Features
- **Semantic Text Analytics Integration**  
  Connects MCP clients to the Dandelion semantic text analytics API.

- **NLP Capabilities**  
  Provides natural language processing functions such as semantic analysis and related text understanding tasks (as supported by Dandelion’s API).

- **Entity Extraction**  
  Supports extraction of entities from text (e.g., named entities), exposing Dandelion’s NER capabilities through MCP.

- **Static MCP Server URL**  
  Uses a single static MCP endpoint (`https://mcp.pipedream.net/v2`) that works across compatible MCP clients.

- **Client-Agnostic Integration**  
  Designed to be added to various MCP-capable chat or agent clients using the same server URL.

- **Authentication at Configuration Time**  
  Authentication is handled when adding the server to an application/client, not by changing the URL.

## Integration & Usage
- Add the MCP server to your MCP-compatible chat or agent client using:  
  `https://mcp.pipedream.net/v2`
- Configure authentication within your client according to its MCP server setup flow.
- Refer to the platform’s Configuration page (Pipedream Connect) for detailed setup instructions.

## Images & Media
- **Brand logo:** ![Dandelion logo](https://dandelion.eu/images/logo-dandelion.png)
- **Example screenshot:** ![Dandelion NER screenshot](https://dandelion.eu/images/screenshots/dandelion-ner.png)

## Pricing
No pricing information is provided in the available content.