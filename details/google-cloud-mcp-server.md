## Google Cloud MCP Server

**Category:** Cloud & DevOps MCP Servers  
**Brand:** Google Cloud  
**Source:** https://mcp.pipedream.com/app/google_cloud  
**MCP Server URL:** `https://mcp.pipedream.net/v2`

### Overview
The Google Cloud MCP Server provides an MCP-compatible interface to Google Cloud Platform services, including BigQuery, Cloud Storage, Compute Engine, and Cloud Logging. Once configured with your Google Cloud account, it exposes multiple operations as tools that can be invoked from compatible MCP clients.

### Features

- **Unified MCP Endpoint**
  - Single static MCP server URL (`https://mcp.pipedream.net/v2`) usable from any supported client.
  - Authentication handled when adding the server to your MCP-enabled application.

- **Account Integration**
  - Connect a Google Cloud account and configure it once to access the available tools.

- **Email / Workspace Administration**
  - **Update Signature for Email in Organization**
    - Update the signature for a specific email address in a Google Workspace organization.
    - Requires a Google Cloud service account with delegated domain-wide authority.

- **Cloud Storage (GCS)**
  - **Upload An Object**
    - Upload an object to a Google Cloud Storage bucket.
  - **Search Objects**
    - Search objects in a bucket using a prefix.
  - **List Buckets**
    - List Google Cloud Storage buckets within the configured project / account.
  - **Get Object**
    - Download an object from a Google Cloud Storage bucket.
  - **Get Bucket Metadata**
    - Retrieve metadata for a Google Cloud Storage bucket.
  - **Create Bucket**
    - Create a new bucket in Google Cloud Storage.

- **BigQuery**
  - **Run Query**
    - Execute SQL queries in BigQuery.
  - **BigQuery Insert Rows**
    - Insert rows into an existing BigQuery table.
  - **Create Scheduled Query**
    - Create a scheduled query job in Google Cloud / BigQuery.

- **Compute Engine**
  - **Switch Instance Boot Status**
    - Start or stop a virtual machine instance by toggling its boot status.

- **Cloud Logging**
  - **Logging – Write Log**
    - Write log entries to Google Cloud Logging.

### Tools Summary
- Total of **12 actions** exposed as MCP tools across:
  - Google Workspace (email signatures)
  - Cloud Storage (buckets and objects)
  - BigQuery (queries, inserts, scheduled queries)
  - Compute Engine (instance start/stop)
  - Cloud Logging (write logs)

### Pricing
No pricing information is provided in the available content. Use of this MCP server may be subject to Pipedream and Google Cloud Platform billing, as configured in your own accounts.