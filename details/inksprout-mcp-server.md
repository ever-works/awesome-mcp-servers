# Inksprout MCP Server

## Overview
Inksprout MCP Server is an integration that connects Inksprout’s link summarization and LinkedIn post drafting capabilities to MCP-compatible chat clients and tools via a static MCP endpoint.

- **Type:** MCP server integration
- **Category:** Content extraction & summarization
- **Provider / Brand:** Inksprout (via Pipedream Connect)
- **Primary Use Cases:**
  - Automatically summarize links
  - Draft LinkedIn posts based on shared links
  - Edit and personalize generated content before publishing

## Features
- **Automated Link Summarization**  
  - Generates a summary when sharing links (e.g., articles, web pages).  
  - Designed to pre-fill content (such as a social post) from the link’s key points.

- **LinkedIn Post Drafting**  
  - Automatically fills a LinkedIn post with a summary of the shared link.  
  - Supports subsequent manual editing and personalization of the draft.  
  - Allows users to save the final version after adjustments.

- **MCP Server Integration**  
  - Exposes Inksprout functionality via a single, static MCP server URL:  
    - `https://mcp.pipedream.net/v2`  
  - Same URL can be used by all compatible MCP clients.  
  - Authentication is performed when adding the server to an application.

- **Client-Agnostic Setup**  
  - Can be added to multiple MCP-capable chat clients.  
  - Configuration guidance provided via a general configuration page (not client-specific in this summary).

## Technical Details
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`  
- **Integration Layer:** Powered by Pipedream Connect  
- **Authentication:** Occurs during server addition/registration in the client

## Pricing
The provided content does not include any pricing or plan details for Inksprout MCP Server.