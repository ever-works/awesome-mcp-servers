# Miro Developer App MCP Server

## Overview
The Miro Developer App MCP Server integrates Miro’s visual collaboration and whiteboarding platform into MCP-compatible tools and chat clients. It exposes Miro board and item operations as MCP tools, enabling you to create, read, update, and delete Miro content directly from your MCP workflows.

- **Category:** Project Management MCP Servers
- **Vendor / Brand:** Miro (via Pipedream)
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL that works for all clients, with authentication handled when adding the server to your application.
- Can be added to various chat clients and MCP-compatible apps for interactive whiteboarding operations.

### Board Management
- **Create Board** – Programmatically create new Miro boards.
- **Get Board** – Retrieve details of a specific Miro board.
- **List Boards** – Return a list of a user’s Miro boards.
- **Update Board** – Modify properties of an existing Miro board.
- **Delete Board** – Remove a Miro board.

### Item & Content Management on Boards
- **Get Items** – Fetch items on a given Miro board.
- **Get Specific Item** – Retrieve a specific item from a Miro board by identifier.
- **Delete Item** – Delete an item from a Miro board.

### Sticky Notes
- **Create Sticky Note** – Create a sticky note on a Miro board.
- **Update Sticky Note** – Update the content of an existing sticky note.

### Shapes
- **Create Shape** – Add a new shape item to a Miro board.
- **Update Shape** – Update the content / properties of an existing shape.

### Card Items
- **Create Card Item** – Create a card item on a Miro board.
- **Update Card Item** – Update an existing card item.

## Available Tools
- 14 actions exposed as MCP tools covering board-level and item-level CRUD operations for boards, sticky notes, shapes, and card items.

## Pricing
Pricing information is not provided in the available content. Use of this MCP server is provided through Pipedream; any costs would follow Pipedream’s and Miro’s standard pricing and usage terms.