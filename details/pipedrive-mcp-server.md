## Pipedrive MCP Server

### Overview
Pipedrive MCP Server is an MCP-compatible integration endpoint that connects applications (such as chat clients) to Pipedrive, a sales-focused CRM platform. It exposes a set of ready-made actions for managing people, organizations, deals, leads, and notes in Pipedrive via a static MCP server URL.

**MCP Server URL:** `https://mcp.pipedream.net/v2`

---

### Features

#### MCP Server & Configuration
- Static MCP server URL usable with any compatible client.
- Connect Pipedrive account via sign-in and OAuth-based authentication.
- Can be added to various chat clients or applications as an MCP server.
- Central configuration through the Pipedream configuration page (for setup and reference).

#### Available Tools (Actions)
The server currently exposes **17 actions** as tools (the following are listed explicitly in the content):

##### People (Persons)
- **Add Person**  
  - Create a new person in Pipedrive.  
  - Uses Pipedrive’s People API.

- **Update Person**  
  - Update an existing person’s data (e.g., fields, contact info) by ID.

- **Get person details**  
  - Retrieve full details of a person by their ID.

- **Search persons**  
  - Search all persons by name, email, phone, notes, and/or custom fields.  
  - Wrapper around `/v1/itemSearch` with a narrower OAuth scope.  
  - Supports filtering found persons by Organization ID.

- **Merge Persons**  
  - Merge two persons into a single record.

##### Deals
- **Update Deal**  
  - Update properties of an existing deal using Pipedrive’s Deals API.

- **Merge Deals**  
  - Merge two deals into one consolidated record.

##### Leads
- **Add Lead**  
  - Create a new lead in Pipedrive.

- **Get Lead by ID**  
  - Retrieve a lead by its unique ID.

- **Get All Leads**  
  - Fetch all leads from Pipedrive.

- **Search Leads**  
  - Search for leads by name or email.

##### Organizations
- **Add Organization**  
  - Create a new organization in Pipedrive using the Organizations API.

##### Notes
- **Add Note**  
  - Add a new note in Pipedrive.

- **Search Notes**  
  - Search for notes in Pipedrive.

- **Remove Duplicate Notes**  
  - Identify and remove duplicate notes from an object in Pipedrive (uses underlying get-notes and delete-notes capabilities).

> Note: The content states there are **17 actions** available as tools; only those explicitly listed above are described in the provided text.

---

### Category & Use Cases
- **Category:** Business & Commerce – MCP Servers
- **Primary use cases:**
  - Integrate Pipedrive CRM operations into chat-based or MCP-compatible applications.
  - Automate CRM tasks like creating and updating people, organizations, deals, leads, and notes.
  - Search, retrieve, and clean up CRM data (e.g., deduplicating notes, merging records).

---

### Pricing
No pricing information for the Pipedrive MCP Server is provided in the available content.