# Clerk MCP Server

An MCP server integration for Clerk that lets MCP-based agents access Clerk’s authentication and user management APIs for React and React Native applications.

---

## Overview
- **Category:** Security / Attestation / MCP Servers
- **Brand:** Clerk
- **Source URL:** https://mcp.pipedream.com/app/clerk
- **Static MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Intended use:** Give AI agents and MCP-compatible chat clients programmatic access to Clerk user and organization data and management operations.

---

## Features

### MCP Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across clients.
- Works with MCP-compatible chat clients (e.g., ChatGPT/OpenAI) via configuration guides.
- Authentication handled when the server is added to the client/application.

### Clerk Account Integration
- Connects to an existing Clerk account.
- Operates against Clerk’s backend APIs for authentication and user management.
- Suitable for React and React Native applications using Clerk.

### Available Tools (Actions)
The Clerk MCP Server exposes the following actions as MCP tools:

1. **Update User**
   - Update a user’s attributes.
   - Set primary contact identifiers:
     - `Primary Email Address Id`
     - `Primary Phone Number Id`
   - Requires that the IDs correspond to verified identifications belonging to the user.

2. **Get User**
   - Retrieve details of a specific user.
   - Uses Clerk’s backend API to return user profile and related attributes.

3. **Get User Memberships**
   - Retrieve a list of an individual user’s organization memberships.
   - Useful for authorization and role/organization-aware workflows.

4. **Delete User**
   - Delete a specified user from Clerk.
   - Supports automated deprovisioning and account removal flows.

5. **Create User**
   - Create a new Clerk user.
   - Behavior is governed by the application’s existing user management settings and configuration (e.g., required fields, verification rules).

6. **Create User Invitation**
   - Create a new invitation for a specified email address.
   - Sends an invitation email through Clerk.
   - Constraints:
     - Cannot create an invitation if one already exists for the given email.
     - Attempting to invite an email that already exists as a user in the application results in an error.

---

## Pricing

No pricing information for the Clerk MCP Server is provided in the referenced content.