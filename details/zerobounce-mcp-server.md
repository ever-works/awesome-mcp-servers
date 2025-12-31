# ZeroBounce MCP Server

ZeroBounce MCP Server is an MCP-compatible integration that gives AI agents access to ZeroBounce’s email validation and deliverability services via Pipedream.

## Overview
- **Type:** MCP server / developer tool
- **Category:** Business & Commerce – MCP servers
- **Purpose:** Enable chat clients and AI agents to validate emails, process bulk validation files, retrieve validation results, and score email reliability using ZeroBounce.
- **Base MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Server Integration
- Static MCP server URL that works across supported clients.
- Authentication handled when adding the server to your application.
- Designed to be added to various chat clients or AI agent environments.
- Configuration guidance available via a dedicated configuration page (client-specific setup instructions).

### Available Tools (Actions)
The MCP server exposes four primary ZeroBounce tools as actions:

1. **Validate Email**
   - Validates a single, specific email address.
   - Uses ZeroBounce’s validation API to check if an email is valid, invalid, or otherwise risky.
   - Intended to reduce bounces and improve inbox placement for individual addresses.

2. **Get Validation Results File**
   - Downloads validation results for a file previously submitted via ZeroBounce’s `sendfile` API.
   - Allows asynchronous / batch workflows where email lists are uploaded and results retrieved later through the MCP server.

3. **Validate Emails in File**
   - Performs bulk email validation on all addresses contained in an uploaded file.
   - Supports list-level cleaning workflows for campaigns, CRMs, or large contact databases.

4. **AI Scoring**
   - Generates an AI-based reliability score for a given email address.
   - Uses ZeroBounce’s AI models to estimate how reliable or risky an email is, aiding deliverability and list quality decisions.

## Use Cases
- Integrate email validation into AI assistants or chat-based workflows.
- Automatically validate user-submitted emails in conversational flows.
- Bulk-clean email lists from within an AI or chat client using file-based validation.
- Score email reliability with AI to prioritize or filter contacts.

## Pricing
- No specific pricing information for the ZeroBounce MCP Server or its usage is provided in the source content.
- Any costs would likely follow the underlying ZeroBounce and/or Pipedream pricing models (not detailed in the provided text).