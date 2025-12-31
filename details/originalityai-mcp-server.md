# Originality.ai MCP Server

An MCP server that connects to Originality.ai so MCP clients can run AI-generated content detection and plagiarism checks.

---

## Overview
- **Type:** MCP Server (Model Context Protocol)
- **Category:** Security & Attestation MCP Servers
- **Brand:** Originality.ai
- **Slug:** `originalityai-mcp-server`
- **Base MCP URL:** `https://mcp.pipedream.net/v2`

This server exposes Originality.ai’s detection capabilities as MCP tools that can be used from compatible chat clients (e.g., ChatGPT with MCP support).

---

## Features

### MCP Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across clients.
- Authentication handled when adding the server within the client/application.
- Configuration guided via a dedicated configuration page on Pipedream.
- Works with multiple MCP-compatible chat clients (e.g., ChatGPT by OpenAI).

### Available Tools (Actions)
The server currently exposes **3 actions** as MCP tools:

1. **Scan Content for Plagiarism and Readability**
   - Input: Text/string content.
   - Capabilities:
     - Checks the text for plagiarism.
     - Performs readability analysis on the same text.
   - Intended use: Evaluating originality and readability of draft content before publishing.

2. **Detect AI From URL**
   - Input: URL of a webpage.
   - Capabilities:
     - Scans the webpage content.
     - Detects AI-generated content within the page.
   - Intended use: Auditing online pages for AI-written material.

3. **Detect AI Content**
   - Input: Text/string content.
   - Capabilities:
     - Analyzes the text for signs of AI generation.
   - Intended use: Verifying whether specific content segments are likely AI-generated.

---

## Use Cases
- Checking articles, blog posts, and marketing copy for plagiarism before publication.
- Assessing whether submitted content (e.g., from freelancers or students) is AI-generated.
- Auditing existing webpages for AI-generated content.
- Evaluating readability of content for content quality and audience fit.

---

## Pricing
No pricing information is provided in the available content. Use of this MCP server may require an Originality.ai account and/or a Pipedream account; refer to the Originality.ai and Pipedream sites for current pricing details.

---

## Links
- **MCP Server Page:** https://mcp.pipedream.com/app/originality_ai
- **MCP Configuration:** https://mcp.pipedream.com/configuration
- **Scan Content for Plagiarism and Readability (docs):** https://github.com/PipedreamHQ/pipedream/blob/master/components/originality_ai/actions/scan-content-for-plagiarism-and-readability/scan-content-for-plagiarism-and-readability.mjs
- **Detect AI From URL (docs):** https://github.com/PipedreamHQ/pipedream/blob/master/components/originality_ai/actions/detect-ai-from-url/detect-ai-from-url.mjs
- **Detect AI Content (docs):** https://github.com/PipedreamHQ/pipedream/blob/master/components/originality_ai/actions/detect-ai-content/detect-ai-content.mjs
- **Originality.ai Docs (general):** https://docs.originality.ai/introduction