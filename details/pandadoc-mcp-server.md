# PandaDoc MCP Server

**Category:** Document Management MCP Servers  
**Brand:** PandaDoc  
**Source:** https://mcp.pipedream.com/app/pandadoc

## Overview
PandaDoc MCP Server exposes PandaDoc’s document management and e‑signature capabilities as tools that can be called from MCP-compatible applications. It supports AI-driven workflows to create, send, track, and sign documents via the PandaDoc platform.

## Features

### MCP Server & Connection
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
- Authentication handled when adding the server to your MCP-compatible application  
- Usable from multiple chat / client applications via standard MCP configuration  
- Integrates with existing PandaDoc accounts for document and contact management

### Document Creation
- **Create Document From Template**  
  - Generate a new document from an existing PandaDoc template.  
  - Useful for standardized contracts, proposals, quotes, and other repeatable document types.

- **Create Document From File**  
  - Create a new document from an uploaded file or a public file URL.  
  - Enables converting external documents into PandaDoc-managed documents for e-signature and tracking.

### Document Sending & E‑Signature
- **Send Document**  
  - Move a document to “sent” status.  
  - Optionally send an email to recipients.  
  - Triggers the e‑signing process from within PandaDoc.

### Document Organization & Storage
- **List Folders**  
  - Retrieve a list of folders that contain documents.  
  - Supports navigating and organizing document storage within PandaDoc.

- **Create Folder**  
  - Create a new folder to store and organize documents.

### Document Retrieval & Downloads
- **List Documents**  
  - List documents in the account.  
  - Supports optional filtering by search query or tags.

- **Get Document Details**  
  - Return detailed metadata and data about a specific document.

- **Get Document Status**  
  - Retrieve basic status information (e.g., sent, viewed, completed) for a document.

- **Download Document**  
  - Download a document as a PDF.

- **Download Protected Document**  
  - Download a completed document as a verifiable PDF (for audit / verification purposes).

### Attachments
- **List Document Attachments**  
  - Return a list of attachments associated with a specified document.

- **Create Document Attachment**  
  - Add an attachment to a document (e.g., supporting files, additional references).

### Contacts
- **List Contacts**  
  - List all contacts within the PandaDoc account.

- **Create or Update Contact**  
  - Add or update a contact using the email address as the unique index.  
  - Helps keep recipient and stakeholder information current for document workflows.

## Available Tools
- 14 actions available as MCP tools, including (from the provided list):
  - Send Document  
  - List Folders  
  - List Documents  
  - List Document Attachments  
  - List Contacts  
  - Get Document Status  
  - Download Protected Document  
  - Download Document  
  - Get Document Details  
  - Create or Update Contact  
  - Create Folder  
  - Create Document From Template  
  - Create Document From File  
  - Create Document Attachment

## Pricing
No pricing information is provided in the supplied content. Users should refer to the PandaDoc or Pipedream/Workday sites for current pricing details.