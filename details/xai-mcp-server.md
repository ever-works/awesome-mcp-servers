# xAI MCP Server

xAI MCP Server exposes xAI capabilities through the Model Context Protocol (MCP), allowing MCP-compatible agents and chat clients to access xAI language and embedding models via a unified server endpoint.

---

## Overview
- **Category:** AI Integration – MCP Servers  
- **Provider / Brand:** xAI (via Pipedream)  
- **Protocol:** Model Context Protocol (MCP)  
- **Purpose:** Integrate xAI language and embedding models into MCP-enabled applications for advanced AI-assisted tasks (text generation, chat, embeddings, and model discovery).

---

## Configuration & Access
- **MCP Server URL (static for all clients):** `https://mcp.pipedream.net/v2`  
- **Authentication:** Performed when adding the server to your MCP-compatible application or chat client.  
- **Client setup:** Add the above MCP server URL in your chat client or MCP agent configuration; follow the client-specific instructions or the Pipedream Configuration page.

---

## Features

### Core Capabilities
- **Expose xAI models via MCP**  
  - Provides a single MCP endpoint that allows applications to interact with xAI’s language and embedding models.

- **MCP-compatible integration**  
  - Designed for use with MCP agents and MCP-aware chat clients.

### Available Tools (Actions)
1. **Post Completion**  
   - Creates a language model response for a given prompt.  
   - Suitable for single-turn text generation (e.g., drafting content, answering questions from a static prompt).

2. **Post Chat Completion**  
   - Generates a language model response for a multi-message chat conversation.  
   - Supports conversational AI use cases with context from prior messages.

3. **Get Model**  
   - Lists all available xAI language and embedding models.  
   - Enables dynamic model selection and discovery inside MCP agents.

4. **Create Embedding**  
   - Creates embedding vector representations for input text.  
   - Useful for semantic search, similarity matching, retrieval-augmented generation, and other embedding-based workflows.

### Operational Details
- **Static endpoint for all clients:** The same MCP URL is used across different chat clients and MCP-compatible tools.  
- **Documentation links:** Each tool has associated documentation in the Pipedream GitHub repository for parameter structures and example usage.

---

## Pricing
The provided content does not include any pricing information or plan details for the xAI MCP Server or related xAI usage. Refer to the provider’s site (xAI and/or Pipedream) for current pricing and billing terms.