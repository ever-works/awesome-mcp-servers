# Google Gemini MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** Google  
**Source:** https://mcp.pipedream.com/app/google_gemini

## Overview
The Google Gemini MCP Server exposes Google Gemini’s multimodal AI capabilities—covering text, images, and more—through the Model Context Protocol (MCP). It provides a static MCP server endpoint that can be added to compatible clients (such as ChatGPT via MCP) to generate content and embeddings using the Google Gemini API.

## Features
- **Static MCP Server Endpoint**  
  - Single URL for all compatible MCP clients:  
    - `https://mcp.pipedream.net/v2`  
  - Authentication handled when adding the server to your application.

- **Multimodal AI Integration**  
  - Leverages Google Gemini, a multimodal AI by DeepMind.  
  - Supports processing of text and images (and more, per Gemini capabilities; audio mentioned at the AI level though not exposed as a separate action here).

- **Available Tools (Actions)**  
  1. **Generate Embeddings**  
     - Generate embeddings from text input using Google Gemini.  
     - Intended for tasks like semantic search, similarity, or vector storage.  
     - Source: `generate-embeddings` action (GitHub-linked implementation).

  2. **Generate Content from Text**  
     - Generate AI content from text-only input via the Google Gemini API.  
     - Suitable for drafting, rewriting, summarization, and other text generation tasks.  
     - Source: `generate-content-from-text` action.

  3. **Generate Content from Text and Image**  
     - Generate content using both text and image input through the Gemini API.  
     - Enables vision + language use cases such as image interpretation with textual instructions.  
     - Source: `generate-content-from-text-and-image` action.

- **Client Integration Guidance**  
  - Documentation and configuration instructions available via the MCP configuration page.  
  - Example integration guidance for ChatGPT (OpenAI) as an MCP client.

- **Account Connection Flow**  
  - Sign-in flow to connect a Google Gemini account and manage connections before using the MCP server.

## Pricing
Pricing details are not provided in the available content. Use of the server and API may be subject to Pipedream and Google Gemini billing; consult their respective pricing pages for specifics.