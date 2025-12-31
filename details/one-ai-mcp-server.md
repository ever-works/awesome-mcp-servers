# One AI MCP Server

APIs that make your app understand language, exposed via the Model Context Protocol (MCP) through Pipedream Connect.

## Overview
- **Type:** MCP server / AI integration
- **Category:** AI Integration – MCP Servers
- **Provider/Brand:** One AI (via Pipedream Connect)
- **Use cases:** Summarization of conversations, categorization of text/articles, and other language understanding tasks for MCP-based agents and tools.
- **MCP Server URL:** `https://mcp.pipedream.net/v2` (static URL used by all clients; authentication is added in your application/client configuration)

## Features
- **Language Understanding APIs**  
  - General-purpose NLP capabilities exposed via MCP.  
  - Designed for integrating language understanding into applications and MCP-compatible agents.

- **Summarization**  
  - Summarize conversations and other text content.  
  - Suitable for chat transcripts, documents, and similar text sources.

- **Categorization**  
  - Categorize articles and other text inputs.  
  - Enables basic content labeling and classification workflows.

- **MCP Integration**  
  - Exposes One AI language APIs as an MCP server.  
  - Works with MCP-compatible chat clients and tools.  
  - Uses a single static server URL (`https://mcp.pipedream.net/v2`) for all clients.

- **Client-Agnostic Setup**  
  - Same MCP endpoint for every client; configuration handled per client/application.  
  - Authentication is configured when adding the server to your app or chat client.

- **Configuration Resources**  
  - A dedicated configuration page (linked from the app) with client-specific setup instructions.

## Integration & Setup
- **Step 1:** Use the static MCP server URL: `https://mcp.pipedream.net/v2`.
- **Step 2:** Add the server to your MCP-compatible chat client or application.  
- **Step 3:** Configure authentication within your client/app as instructed in the configuration docs.

## Pricing
- Not specified in the provided content.

## Additional Details
- **Source URL:** https://mcp.pipedream.com/app/one_ai
- **Brand Logo:** https://www.oneai.com/favicon-196x196.png
- **Tags:** `nlp`, `summarization`, `ai-integration`