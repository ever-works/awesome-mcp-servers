# GPTZero MCP Server

**Category:** Security & Attestation MCP Servers  
**Brand:** GPTZero  
**Slug:** gptzero-mcp-server

## Description
GPTZero MCP Server is a Model Context Protocol (MCP) server that exposes GPTZero’s AI-generated text detection capabilities to MCP-compatible clients. It allows applications and chat clients to submit text for AI content checking and classification, enabling detection of AI-generated content (e.g., from ChatGPT and other models) within an MCP-based workflow.

## Features
- **MCP-compatible AI detection service**: Provides access to GPTZero’s AI-generated text detection and classification via the MCP standard.
- **AI content checking**: Allows clients to check whether text is likely AI-generated, targeting content produced by ChatGPT and other AI models.
- **Static MCP server endpoint**: Uses a single static URL that works across clients:
  - `https://mcp.pipedream.net/v2`
- **Works with multiple MCP clients**: Designed to be added to any MCP-capable chat client or application.
- **Authentication at client setup**: Authentication is performed when adding the server to the client/app (specific method handled during configuration).
- **Hosted by Pipedream Connect**: Runs as a managed MCP server through Pipedream’s infrastructure, avoiding self-hosting.

## Integration & Usage
- Add the server URL to your MCP-compatible chat client or application.
- Configure authentication when prompted by the client during server addition.
- Reference the provider as “GPTZero: Detect AI” within Pipedream Connect.

## Pricing
Pricing details are not provided in the available content.

## Tags
- ai-detection  
- content-detection  
- plagiarism
