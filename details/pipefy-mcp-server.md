# Pipefy MCP Server

## Overview
Pipefy MCP Server is an MCP (Model Context Protocol) server that exposes low-code Pipefy process and workflow management operations—such as pipelines (pipes), cards, and database tables—directly into MCP-compatible applications. It is provided by Pipedream and connects to a Pipefy account via a static MCP server URL.

- **Category:** Workflow Automation MCP Servers
- **Provider / Brand:** Pipefy (via Pipedream)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL that works for all clients; authentication happens when adding the server to an MCP-compatible app.
- Can be added to various chat or MCP clients using standard MCP configuration.

### Pipe (Pipeline) Management
- **Create Pipe**
  - Create new pipes (workflows/pipelines) in Pipefy.

- **Look up Pipe by ID**
  - Retrieve details of an existing pipe using its ID.

### Card Management
- **Create Card**
  - Create a new card in a specified pipe.

- **Update Card**
  - Modify an existing card’s properties.

- **Update Card Field**
  - Update individual card fields within a pipe.

- **Look up Card by ID**
  - Retrieve a specific card’s details using its ID.

- **Get All Cards**
  - Fetch all cards in a given pipe.

- **Delete Card**
  - Delete an existing card from a pipe.

### Table (Database) Management
- **Update Table**
  - Update properties / configuration of an existing table.

- **Update Table Record**
  - Modify an existing record in a table.

- **Create Table Record**
  - Create a new record in a table.

- **Look Up Table by ID**
  - Retrieve a database table using its ID.

- **Get Table Records**
  - Fetch all records from a specified table.

### Phase Management
- **Look Up Phase by ID**
  - Retrieve details of a phase in a pipe using its ID.

### User Information
- **Get Current User**
  - Return information about the currently authenticated Pipefy user.

### Tool Summary
- Total of **15 actions** exposed as MCP tools, covering:
  - Pipe creation and lookup
  - Card creation, update, deletion, lookup, and listing
  - Table update, record creation/update, table lookup, and record listing
  - Phase lookup
  - Current user information

## Configuration
- **Server URL:** `https://mcp.pipedream.net/v2` (static for all clients)
- Added to MCP-compatible apps via their MCP configuration flow (per-client instructions provided on the configuration page referenced by the product).

## Pricing
The provided content does not list any pricing or plans for the Pipefy MCP Server. Pricing information is not specified.