# Microsoft Outlook MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Microsoft  
**Source:** https://mcp.pipedream.com/app/microsoft_outlook

Microsoft Outlook MCP Server connects Outlook email, contacts, and calendar data to the MCP ecosystem via a static MCP server URL, allowing tools and chat clients to send and manage emails, contacts, and related resources programmatically.

---

## Features

### MCP Server & Connectivity
- Static MCP server endpoint for all clients: `https://mcp.pipedream.net/v2`
- Works with multiple chat / MCP clients; authentication occurs when adding the server to the client or application
- Centralized connection for Microsoft Outlook accounts to MCP-based tools

### Email Management Tools (Actions)
- **Send Email**
  - Send an email to one or multiple recipients.
- **Reply to Email**
  - Reply to an existing email in Microsoft Outlook.
- **Create Draft Email**
  - Create a draft email for later review or sending.
- **Find Email**
  - Search for an email in a user’s mailbox based on specified criteria.
- **Find Shared Folder Email**
  - Search for an email in a shared Outlook folder.
- **Move Email to Folder**
  - Move an email to a specified folder.
- **Remove Label from Email**
  - Remove a label/category from an email.
- **Download Attachment**
  - Download an email attachment to the `/tmp` directory.

### Contacts Management Tools
- **Create Contact**
  - Add a new contact to the root Contacts folder.
- **Update Contact**
  - Update an existing contact’s details.
- **List Contacts**
  - Retrieve a collection of contacts from the default Contacts folder.
- **Find Contacts**
  - Search contacts using a given search string.

### Labels & Folders
- **List Labels**
  - Retrieve all labels/categories defined for a user.
- **List Folders**
  - Retrieve a list of all folders in Microsoft Outlook.

> Note: The page references “16 actions available as tools”; only the actions explicitly listed in the provided content are documented above.

---

## Configuration
- Use the static MCP server URL `https://mcp.pipedream.net/v2` when adding the server to your MCP-compatible client.
- Authentication is performed when the server is added to the application or chat client.
- Additional client-specific setup details are available on the product’s configuration page (not reproduced here).

---

## Pricing
- No pricing information is provided in the available content.