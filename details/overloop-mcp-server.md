# Overloop MCP Server

## Overview
Overloop MCP Server is an integration that exposes Overloop’s CRM and sales automation capabilities as tools within MCP-compatible chat or automation clients. It allows you to manage contacts, organizations, deals, and workflows programmatically via a single MCP server endpoint.

- **Type:** MCP Server integration
- **Category:** Business & Commerce
- **Platform:** Overloop (CRM & sales automation)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Server & Configuration
- Static MCP server URL that works for all clients.
- Authentication handled when adding the server to your MCP-compatible application.
- Can be added to various chat/automation clients (via their MCP configuration).

### Available Tools (Actions)
17 Overloop actions are exposed as MCP tools:

#### Organization Management
- **Create Organization** – Create a new organization record in Overloop.
- **Update Organization** – Update details of an existing organization.
- **Get Organization** – Retrieve an organization by ID.
- **Enroll Organization** – Enroll an organization into a workflow.

#### Deal Management
- **Create Deal** – Create a new deal in a pipeline.
- **Update Deal** – Update an existing deal’s properties.
- **Get Deal** – Retrieve a deal by ID.
- **Move Deal** – Move a deal to another stage or position.
- **Mark Deal as Won** – Set a deal’s status to won.
- **Mark Deal as Lost** – Set a deal’s status to lost.
- **Enroll Deal** – Enroll a deal into a workflow.

#### Contact Management
- **Create Contact** – Create a new contact in Overloop.
- **Update Contact** – Update an existing contact’s details.
- **Get Contact** – Retrieve a contact by ID.
- **Exclude Contact** – Add a contact to the exclusion list.
- **Enroll Contact** – Enroll a contact into a workflow.
- **Add Contact to Campaign** – Add a contact to a specific campaign.

## Pricing
No pricing information is provided in the available content for the Overloop MCP Server integration. Pricing may depend on the underlying Overloop and/or Pipedream plans and should be checked on their respective websites.