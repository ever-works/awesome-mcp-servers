# DocuGenerate MCP Server

An MCP server integration for DocuGenerate that enables automated generation and management of PDF documents (such as invoices, letters, contracts, agreements, and certificates) via MCP-compatible applications.

---

## Overview

- **Type:** MCP server / API integration
- **Category:** Document management MCP servers
- **Provider / Brand:** DocuGenerate (via Pipedream)
- **Primary Use Cases:**
  - Generate PDF documents from templates
  - Manage document templates
  - Retrieve, update, and delete generated documents and templates

---

## Features

### MCP Server & Connectivity
- **Static MCP server URL:** `https://mcp.pipedream.net/v2` (used to connect from compatible clients).
- **Client-agnostic URL:** Same server URL works for every supported client; authentication is handled when adding the server to the application.
- **Account connection:** Ability to connect a DocuGenerate account and select a client to start using the tools.
- **Configuration guidance:** Instructions and a dedicated configuration page on how to add and use the server with different chat or MCP clients.

### Document Generation & Management
- **Generate Document**
  - Generates a document (typically PDF) from a selected template.
  - Suitable for invoices, letters, contracts, agreements, certificates, and other structured documents.

- **List Documents**
  - Retrieves a list of documents generated from a given template.
  - Useful for tracking or managing multiple outputs based on the same template.

- **Get Document**
  - Retrieves details or content for a specific document.

- **Update Document**
  - Updates a specific document (e.g., metadata or certain fields, depending on DocuGenerate’s API capabilities).

- **Delete Document**
  - Deletes a specific document from the DocuGenerate account.

### Template Management
- **List Templates**
  - Retrieves all available templates in the connected DocuGenerate account.

- **Get Template**
  - Retrieves a specific template’s details.

- **Delete Template**
  - Deletes a specific template from the DocuGenerate account.

### Available Tools Summary (Actions Exposed as MCP Tools)
1. Generate Document
2. Get Document
3. List Documents
4. Update Document
5. Delete Document
6. List Templates
7. Get Template
8. Delete Template

---

## Technical Details

- **Access method:** MCP-compatible clients connect to the static URL and authenticate to access DocuGenerate tools.
- **Integration layer:** Provided through Pipedream’s infrastructure, exposing DocuGenerate actions as MCP tools.

---

## Pricing

- The provided content does not include any pricing information for DocuGenerate MCP Server or related DocuGenerate services.

---

## Links

- **MCP server URL:** `https://mcp.pipedream.net/v2`
- **Configuration / Documentation (actions):**
  - Update Document: https://github.com/PipedreamHQ/pipedream/blob/master/components/docugenerate/actions/update-document/update-document.mjs
  - List Templates: https://github.com/PipedreamHQ/pipedream/blob/master/components/docugenerate/actions/list-templates/list-templates.mjs
  - List Documents: https://github.com/PipedreamHQ/pipedream/blob/master/components/docugenerate/actions/list-documents/list-documents.mjs
  - Get Template: https://github.com/PipedreamHQ/pipedream/blob/master/components/docugenerate/actions/get-template/get-template.mjs
  - Get Document: https://github.com/PipedreamHQ/pipedream/blob/master/components/docugenerate/actions/get-document/get-document.mjs
  - Generate Document: https://github.com/PipedreamHQ/pipedream/blob/master/components/docugenerate/actions/generate-document/generate-document.mjs
  - Delete Template: https://github.com/PipedreamHQ/pipedream/blob/master/components/docugenerate/actions/delete-template/delete-template.mjs
  - Delete Document: https://github.com/PipedreamHQ/pipedream/blob/master/components/docugenerate/actions/delete-document/delete-document.mjs
- **Source page:** https://mcp.pipedream.com/app/docugenerate