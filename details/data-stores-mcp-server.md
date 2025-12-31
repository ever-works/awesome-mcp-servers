# Data Stores MCP Server

## Overview
Data Stores MCP Server exposes Pipedream Data Stores to MCP-compatible clients, enabling them to persist and manage stateful key–value data across workflows and automations via a standardized MCP endpoint.

- **Provider / Brand:** Pipedream
- **Category:** Database / Messaging MCP Servers
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Use case:** Maintain and share state (key–value data) between tools, workflows, and automations.

## Features

### MCP Server & Connectivity
- Static MCP server URL usable across supported MCP clients.
- Authentication performed when adding the server to your MCP-compatible application.
- Integrates Pipedream Data Stores with chat or other MCP clients so they can read and write state.

### Data Store Operations (Available Tools / Actions)
The server exposes 13 actions as tools for working with Pipedream Data Stores:

1. **Update Record Expiration**  
   - Update the expiration time (TTL) for a record in a Pipedream Data Store.

2. **List Records**  
   - List all records in a specified Pipedream Data Store.

3. **List Keys**  
   - List all keys in a specified Pipedream Data Store.

4. **Check for Existence of Key**  
   - Check if a key exists in a Pipedream Data Store.
   - Optionally create the key if it does not exist.

5. **Get Record (or Create if Not Found)**  
   - Retrieve a single record by key.
   - If the record does not exist, create a new one.

6. **Get Record Keys (by Query)**  
   - Retrieve all record keys in a Data Store that match a provided query.
   - Note: may increase workflow memory usage because it can expose the entire data set from the selected store.

7. **Get Difference Between Data Stores**  
   - Compare two Data Stores.
   - Returns key–value pairs where keys exist in one store but not the other.

8. **Get All Records**  
   - Retrieve all records in a Pipedream Data Store.
   - Note: may increase workflow memory usage as it can expose the full contents of the store.

9. **Delete a Single Record**  
   - Delete one record by key from a Pipedream Data Store.

10. **Delete All Records**  
    - Delete all records from a specified Pipedream Data Store.

11. **Append to Record**  
    - Append a value to an existing record.
    - If the record does not exist, creates a new record with an array value and appends to it.

12. **Add or Update a Single Record**  
    - Create a new record or update an existing record by key.

13. **Add or Update Multiple Records**  
    - Add or update multiple records in a Pipedream Data Store in a single action (bulk operation).

## Use Cases
- Persisting conversation or workflow state between steps or runs.
- Sharing key–value configuration or context between multiple workflows or automations.
- Comparing data sets across Data Stores (e.g., detecting new or missing keys).
- Bulk updating or clearing state as part of automation routines.

## Pricing
No pricing information is provided in the available content.