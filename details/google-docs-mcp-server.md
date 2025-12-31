# Google Docs MCP Server

## Overview
Google Docs MCP Server is an MCP-compatible integration that lets MCP-aware tools and AI agents create, edit, and collaborate on Google Docs. It connects to your Google account and exposes common document operations as tools.

- **Category:** Document-management MCP server
- **Brand:** Google
- **Source URL:** https://mcp.pipedream.com/app/google_docs
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Provides a static MCP server URL usable by any MCP-aware client.
- Authentication occurs when adding the server to your application.
- Can be added to different chat or AI clients as an MCP server.

### Google Docs Document Operations (Tools / Actions)
12 actions are exposed as tools:

1. **Create New Document From Template**
   - Creates a new Google Docs file from an existing template.
   - Supports placeholders in the template document that are replaced via action inputs.

2. **Replace Text**
   - Replaces all instances of matched text in an existing document.
   - Supports Markdown formatting in the replacement text.

3. **Replace Image**
   - Replaces an image in an existing document.

4. **Insert Text**
   - Inserts text at a specified location in a document.

5. **Insert Table**
   - Inserts a table into a document.

6. **Insert Page Break**
   - Inserts a page break into a document.

7. **Get Tab Content**
   - Retrieves the content of a specific tab/section in a document.

8. **Get Document**
   - Retrieves the contents of the latest version of a document.

9. **Find Document**
   - Searches for a specific file by name.

10. **Create a New Document**
    - Creates a new blank Google Docs document.

11. **Append Text**
    - Appends text to the end or a defined position of an existing document.

12. **Append Image to Document**
    - Appends an image to the end of a document.

### File & Account Handling
- Uses Google Docs as online file storage for created and edited documents.
- Connects to your Google account for document access and management.

## Configuration
- Connect your Google account within the Pipedream interface.
- Use the shared MCP server URL (`https://mcp.pipedream.net/v2`) when configuring compatible clients.
- Additional configuration instructions are available on the provider’s configuration page.

## Pricing
Pricing information is not provided in the available content. Use the source URL or provider’s site to check current pricing or plan details.