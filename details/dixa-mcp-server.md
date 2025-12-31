# Dixa MCP Server

MCP server for Dixa, connecting MCP-compatible tools to the Dixa CX platform for managing customer conversations and support data.

**Website:** https://mcp.pipedream.com/app/dixa  
**MCP Server URL:** `https://mcp.pipedream.net/v2`  
**Category:** Business & Commerce – MCP Servers  
**Brand:** Dixa

---

## Overview

Dixa MCP Server exposes Dixa’s CX/CRM capabilities as MCP tools via a static MCP server endpoint hosted by Pipedream. After connecting a Dixa account and authenticating, applications can perform a variety of customer support and conversation-management operations programmatically.

---

## Features

### MCP Server & Configuration
- Static MCP server URL usable for all clients: `https://mcp.pipedream.net/v2`.
- Account connection flow to link a Dixa account before use.
- Usable from multiple MCP-compatible chat clients or applications.

### Conversation Management Tools
- **Create Conversation**
  - Create new email-based or contact-form-based conversations.
- **Get Conversation**
  - Retrieve details of an existing conversation by ID.
- **Close Conversation**
  - Mark a conversation as closed using its ID.
- **Claim Conversation**
  - Claim a conversation for a specific agent.
  - Optional `force` parameter to avoid taking over already-assigned conversations when set to `false`.

### Messaging & Notes
- **Add Message to Conversation**
  - Append a new message to an existing conversation.
- **List Messages**
  - List all messages belonging to a specific conversation.
- **Create Note**
  - Create internal (non-customer-facing) notes attached to a conversation.
- **List Notes**
  - List internal notes from a conversation.

### Tagging & Contact Data
- **Add Tag to Conversation**
  - Assign tags to conversations for categorization or workflow purposes.
- **Set Custom Contact Attributes**
  - Update custom attributes on a contact/user record in Dixa.

### Knowledge Base / Articles
- **Get Article**
  - Retrieve a specific knowledge base article from Dixa.
- **Get Article Translations**
  - Retrieve all translations for a given article.

---

## Pricing

No pricing details are provided in the available content. Pricing for using this MCP server or Pipedream’s platform is not specified here and would need to be obtained from Pipedream or Dixa directly.