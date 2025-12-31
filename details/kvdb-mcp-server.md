# KVdb MCP Server

## Overview
KVdb MCP Server provides Model Context Protocol (MCP) access to KVdb, a globally accessible key–value database designed for quick, simple integration into applications and workflows.

- **Type:** MCP server / integration
- **Category:** Database & Messaging MCP Servers
- **Source URL:** https://mcp.pipedream.com/app/kvdb
- **Underlying service:** KVdb (https://kvdb.io/)

## Features

- **MCP server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL works across supported MCP clients; authentication handled when adding the server to an application.

- **Global key–value storage**  
  - Interfaces with KVdb, a globally accessible key–value database.  
  - Intended for quick and easy integration into projects that require simple key–value persistence.

- **KVdb account integration**  
  - Requires creation of an API key at https://kvdb.io/.  
  - Connects a KVdb account through Pipedream to manage access.

- **Available MCP tools (actions)**  
  1. **Set a Key Value**  
     - Store or update a value for a given key in KVdb via the MCP server.  
  2. **Get a Key Value**  
     - Retrieve the stored value for a given key from KVdb via the MCP server.

- **Client integration**  
  - Can be added to compatible chat or MCP-enabled clients.  
  - Uses a single configuration URL; further details available on the Pipedream configuration page.

## Requirements

- KVdb API key created at https://kvdb.io/.
- MCP-compatible client or application capable of adding external MCP servers.

## Pricing

- No explicit pricing information for KVdb MCP Server or KVdb usage is provided in the referenced content. Users should consult KVdb or Pipedream directly for current pricing details.