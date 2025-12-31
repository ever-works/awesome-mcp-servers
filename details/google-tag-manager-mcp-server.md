# Google Tag Manager MCP Server

**Category:** Workflow Automation MCP Servers  
**Vendor:** Pipedream  
**Slug:** `google-tag-manager-mcp-server`

Google Tag Manager MCP Server lets you programmatically install, store, and manage Google Tag Manager tags from compatible MCP clients (e.g., ChatGPT) via Pipedream.

---

## Features

### Core Capabilities
- Programmatic management of Google Tag Manager from MCP-compatible clients.
- Supports both web and app development use cases where GTM is used to manage tags.
- Single static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
- Authentication handled when adding the server to your application (no per-client URL needed).

### Google Tag Manager Actions (Tools)
The server exposes 5 GTM actions as tools:

1. **Create Tag**  
   - Create a new tag in a specified Google Tag Manager workspace.

2. **Get Tag**  
   - Retrieve details for a specific tag in a workspace.

3. **Get Tags**  
   - Fetch all tags within a given workspace.

4. **Update Tag**  
   - Update an existing tag in a workspace.

5. **Update Variable**  
   - Update a variable in a workspace (e.g., configuration or data layer–related variables used by tags).

### Integration & Configuration
- Connect your Google Tag Manager account and select the relevant client to begin using the server.
- Works with ChatGPT (OpenAI) and other MCP clients that support adding external MCP servers.
- Additional configuration details are available on the Pipedream MCP configuration page (linked from the app).

---

## Use Cases
- Managing marketing and analytics tags across sites and apps via chat or automated workflows.
- Creating, listing, and updating GTM tags without manually using the GTM UI.
- Adjusting GTM variables programmatically as part of broader automation flows.

---

## Pricing
The provided content does not specify any pricing or plans for the Google Tag Manager MCP Server.