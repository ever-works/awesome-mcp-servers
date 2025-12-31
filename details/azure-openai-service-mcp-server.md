# Azure OpenAI Service MCP Server

## Overview
The Azure OpenAI Service MCP Server exposes Azure OpenAI large language models and generative AI capabilities to Model Context Protocol (MCP) compatible clients via a static MCP server endpoint hosted by Pipedream.

- **Type:** MCP server / AI integration
- **Provider / Brand:** Microsoft Azure (hosted via Pipedream)
- **Category:** AI integration – MCP servers
- **Primary Use:** Apply Azure OpenAI LLM and generative AI capabilities across different MCP-compatible chat or automation clients.

## Features
- **MCP-compatible server**
  - Provides a Model Context Protocol server endpoint that can be added to compatible clients.
  - Works with multiple chat clients that support MCP.

- **Static server URL**
  - Single, static endpoint for all supported clients: `https://mcp.pipedream.net/v2`.
  - Same URL can be reused across different applications and environments.

- **Azure OpenAI integration**
  - Connects to Azure OpenAI Service to apply large language models (LLMs) and generative AI.
  - Can be used for a variety of AI use cases supported by Azure OpenAI (e.g., text generation, chat, etc.), depending on your Azure configuration.

- **Account connection flow**
  - Requires configuring Azure OpenAI and connecting your Azure account through Pipedream.
  - Authentication occurs when you add the MCP server to your application.

- **Configurable via Pipedream UI**
  - Guided setup through Pipedream’s “Configure Azure OpenAI” flow.
  - Option to select your client and follow specific instructions.
  - Additional configuration details available via a dedicated configuration page.

- **Tool exposure**
  - Designed to expose Azure OpenAI-powered tools and actions to MCP clients (tool list is dynamically loaded in the Pipedream UI).

## Technical Details
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Authentication:** Performed when adding the server to your MCP-compatible application (details via client-specific instructions / configuration page).

## Pricing
The provided content does not include any pricing or plan information for the Azure OpenAI Service MCP Server or its usage via Pipedream.