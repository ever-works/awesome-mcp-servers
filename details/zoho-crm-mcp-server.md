# Zoho CRM MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Zoho

Zoho CRM MCP Server is an MCP-compatible integration that exposes Zoho CRM’s online sales and marketing capabilities to MCP-based tools and agents via Pipedream. It lets applications interact with Zoho CRM records, modules, and attachments through a standardized MCP server endpoint.

---

## MCP Server Details

- **MCP server URL:** `https://mcp.pipedream.net/v2`  
- **Authentication:** Performed when adding the server to your MCP-compatible application (e.g., chat clients such as ChatGPT via the provided configuration flow).

---

## Features

### Zoho CRM Integration
- Connect a Zoho CRM account to MCP-based tools and agents.
- Work with Zoho CRM’s sales and marketing data via standardized MCP actions.

### Available Tools / Actions (10)

1. **Upload Attachment**  
   - Uploads an attachment file to Zoho CRM from a URL or local file path.

2. **Update Object**  
   - Updates existing entities (records) in a specified module.

3. **Search Objects**  
   - Retrieves records that match user-defined search criteria.

4. **List Objects**  
   - Gets a list of available records from a chosen module.

5. **List Modules**  
   - Retrieves a list of all modules available in the connected Zoho CRM account.

6. **List Fields**  
   - Returns field metadata for a specified module (e.g., field names, structure).

7. **Get Object**  
   - Fetches record data by its ID.

8. **Download Attachment**  
   - Downloads an attachment from Zoho CRM.
   - Saves it to a temporary file system and exposes the file path for use in subsequent steps.

9. **Create Object**  
   - Creates a new record (object) in a specified module.

10. **Convert Lead**  
    - Converts a Lead into a Contact or an Account.

### Configuration & Usage
- Use the static MCP server URL for all clients; authentication occurs when you add the server to your app.
- Configuration guides are available for specific chat clients (e.g., ChatGPT) via the Pipedream MCP configuration page.

---

## Pricing

The provided content does not include any pricing information for the Zoho CRM MCP Server or related usage on Pipedream.