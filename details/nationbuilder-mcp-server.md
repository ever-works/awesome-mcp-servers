# NationBuilder MCP Server

**Category:** Business & Commerce – MCP Servers  
**Brand:** NationBuilder  
**MCP Server URL:** `https://mcp.pipedream.net/v2`

Human-centric tooling for managing nonprofits, causes, campaigns, and movements via the MCP protocol.

---

## Overview

NationBuilder MCP Server is an MCP-compatible server (provided by Pipedream) that exposes NationBuilder CRM actions as tools. It lets you manage people, donations, tags, and memberships in your NationBuilder nation directly from MCP-enabled applications.

---

## Features

### MCP Server & Configuration
- **Static MCP server URL** usable for all clients: `https://mcp.pipedream.net/v2`.
- **Account connection flow**: sign in and connect your NationBuilder account, then select client to start managing data.
- **Works with multiple chat or MCP clients**: add the server to any supported app and authenticate per client.
- Central **configuration documentation** available via the Pipedream configuration page.

### Available Tools (Actions)
The server currently exposes **10 actions as tools**:

1. **Update Person**
   - Update an existing person with provided data fields in NationBuilder.

2. **Update Donation**
   - Update an existing donation record with new or corrected data.

3. **Search Person**
   - Search for a person in NationBuilder using provided criteria.

4. **Remove Tags**
   - Remove one or more tags from a specific person.

5. **Push Person**
   - Attempt to match input person data to an existing person.
   - If a match is found (using one of the supported IDs), the person is updated and a `200` status is returned.
   - If no match is found, a new person is created and a `201` status is returned.
   - Matching can be based on any of:
     - `civicrm_id`
     - `county_file_id`
     - `dw_id`
     - `external_id`
     - `email`
     - `facebook_username`
     - `ngp_id`
     - `salesforce_id`
     - `twitter_login`
     - `van_id`

6. **Delete Donation**
   - Delete a specific donation using its ID.

7. **Create Person**
   - Create a new person record with the provided data.

8. **Create Membership**
   - Create a new membership for a person or entity with specified details.

9. **Create Donation**
   - Create a new donation record in NationBuilder.

10. **Add Tags**
    - Add one or more tags to a specific person.

---

## Pricing

No pricing information is provided in the available content. Refer to the Pipedream website or NationBuilder MCP Server listing for current pricing details.

---

## Links

- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Source / App page:** https://mcp.pipedream.com/app/nationbuilder  
- **Action documentation (examples):**
  - Update Person: https://github.com/PipedreamHQ/pipedream/blob/master/components/nationbuilder/actions/update-person/update-person.mjs
  - Create Person: https://github.com/PipedreamHQ/pipedream/blob/master/components/nationbuilder/actions/create-person/create-person.mjs
  - Create Donation: https://github.com/PipedreamHQ/pipedream/blob/master/components/nationbuilder/actions/create-donation/create-donation.mjs
  - (Similar GitHub paths exist for all other actions listed above.)