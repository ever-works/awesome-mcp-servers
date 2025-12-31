# Perplexity Ask MCP Server

**Category:** Web Search MCP Servers  
**Brand:** Perplexity  
**Source:** https://www.flowhunt.io/mcp-servers/perplexity/

## Overview
Perplexity Ask MCP Server is a Model Context Protocol (MCP) server that integrates the Perplexity Sonar API into MCP‑compatible clients and AI assistants (such as Claude). It enables live web search and real‑time research capabilities directly within development workflows and AI tooling. The server is distributed as an npm package and is typically run via `npx` as an MCP stdio server, using the `PERPLEXITY_API_KEY` environment variable for authentication.

## Features
- **MCP-compatible server implementation**  
  - Implements a Model Context Protocol (MCP) server for use with MCP‑aware clients and AI platforms.

- **Perplexity Sonar / Perplexity API integration**  
  - Connects AI assistants and tools to the Perplexity API.  
  - Provides access to Sonar’s web-wide research and answering capabilities.

- **Live web search**  
  - Performs real-time web searches from within AI assistants and development environments.  
  - Designed to retrieve up‑to‑date information rather than relying solely on static training data.

- **Real-time research workflows**  
  - Supports web-wide research tasks (fact‑finding, comparisons, topical overviews, etc.).  
  - Allows AI agents to enrich their responses with current, external information.

- **Integration with AI assistants and platforms**  
  - Intended for use with assistants like Claude.  
  - Can be integrated into broader AI platforms (e.g., FlowHunt workflows, chatbots, and other MCP‑enabled tools).

- **npm distribution & `npx` execution**  
  - Distributed as an npm package.  
  - Commonly invoked via `npx server-perplexity-ask` (or similarly named entry command) to start the server.

- **Stdio-based MCP server**  
  - Operates as a standard MCP stdio server for straightforward client integration and orchestration.

- **Environment-based authentication**  
  - Uses the `PERPLEXITY_API_KEY` environment variable to authenticate with the Perplexity API.  
  - Keeps secrets outside of code/config files for easier and safer deployment.

## Configuration & Usage (High-Level)
- Install or run via `npx` from the npm package.  
- Configure as an MCP stdio server in your MCP‑compatible client or platform.  
- Set `PERPLEXITY_API_KEY` in the environment so the server can authenticate with the Perplexity API.  
- Once configured, AI assistants and tools can call the server to run live web searches and research queries.

## Pricing
The provided content does not specify any pricing or plans for Perplexity Ask MCP Server.