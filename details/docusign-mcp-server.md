# Docusign MCP Server

Electronic Signature and Agreement Cloud integration for tools and AI agents.

---

## Overview

The Docusign MCP Server exposes DocuSign’s electronic signature and agreement cloud capabilities via MCP (Model Context Protocol), allowing AI agents and other MCP-compatible clients to create, send, and manage envelopes and agreements programmatically.

Server endpoint:

```text
https://mcp.pipedream.net/v2
```

---

## Features

### MCP Server Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across clients.
- Authentication handled when the server is added to your MCP-compatible application (e.g., ChatGPT).
- Designed for use with chat-based and other MCP clients.

### DocuSign Account Connection
- Connect a DocuSign account through Pipedream’s interface.
- Manage multiple DocuSign clients/accounts after connection.

### Available Tools (Actions)

1. **Download Documents**  
   - Downloads the documents of a DocuSign envelope.  
   - Saves files to the `/tmp` directory in the execution environment.  
   - Useful for retrieving completed or in-progress agreement documents.

2. **Create Signature Request (from Template)**  
   - Creates a signature request based on an existing DocuSign template.  
   - Leverages predefined templates to standardize agreements and speed up sending.  
   - Configurable parameters (per the linked action docs) for recipients and template fields.

3. **Create Draft / Send Envelope**  
   - Creates and sends a DocuSign envelope, or creates a draft envelope without sending immediately.  
   - Supports building envelopes dynamically (recipients, documents, and other envelope settings).  
   - Enables workflows where AI or tools prepare drafts for human review before sending.

### Client Integration
- Example guidance available for integrating with **ChatGPT (OpenAI)** as an MCP client.
- Additional configuration options via Pipedream’s general MCP configuration page.

---

## Category
- Business & Commerce → MCP Servers

## Tags
- e-signature
- contracts
- document-automation

---

## Pricing

Pricing details are not provided in the available content. Users should refer to Pipedream or DocuSign pricing pages for cost information related to usage of this MCP server and underlying DocuSign services.