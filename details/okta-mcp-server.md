# Okta MCP Server

## Overview
Okta MCP Server is an MCP-compatible integration that allows AI agents and other MCP tools to interact with Okta’s cloud-based identity and access management (IAM) platform. It supports operations related to user management within Okta, including creating, retrieving, and updating user profiles, and can be used in workflows involving SSO and MFA.

**Category:** Security / Attestation MCP Servers  
**Vendor:** Okta (via Pipedream)  
**MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features
- **MCP-compatible server endpoint**  
  - Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across different MCP clients.  
  - Authentication performed when adding the server to an MCP-compatible application or chat client.

- **Okta identity and access management integration**  
  - Connects to Okta’s cloud-based IAM platform.  
  - Supports workflows involving single sign-on (SSO).  
  - Supports workflows involving multi-factor authentication (MFA).  
  - Enables secure access and management of user identities for applications.

- **Available tools (actions)**
  - **Create User**  
    - Creates a new user in the Okta system.  
    - Exposed as an MCP tool/action for programmatic or AI-driven user provisioning.

  - **Get User**  
    - Fetches information for a specific user from the Okta system.  
    - Useful for querying user profiles, status, and attributes via MCP-enabled clients.

  - **Update User**  
    - Updates the profile of a specific user in the Okta system.  
    - Supports modifying existing user attributes through MCP-based workflows.

## Technical Details
- **Server type:** MCP Server (Model Context Protocol)  
- **Integration host:** Pipedream  
- **Primary scope:** Okta user management (create, read, update)

## Pricing
No pricing information is provided in the available content.