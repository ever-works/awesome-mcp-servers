# Pipedream Utils MCP Server

Utility-focused MCP server providing general-purpose functions and helpers for Pipedream workflows and MCP-based automations.

- **Category:** Workflow Automation MCP Servers
- **Brand:** Pipedream
- **Source:** https://mcp.pipedream.com/app/pipedream_utils
- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- **Actions/Tools Available:** 48 actions exposed as tools

## Overview
Pipedream Utils MCP Server exposes a collection of reusable utility actions that can be called from Pipedream workflows or any MCP-compatible client. These utilities cover text formatting, data transformation, helper functions for workflows, and integrations with services like Amazon S3, Nodemailer, RSS, and scheduling.

## Features

### MCP Server & Configuration
- **Static MCP server URL**: Single URL (`https://mcp.pipedream.net/v2`) usable for all clients.
- **Per-client configuration**: Add the server to different chat / MCP clients and authenticate at the application level.
- **Integration with Pipedream**: Designed to be used directly within Pipedream workflows and MCP-based automations.

### Helper Functions
- **Pretty Print JSON**  
  - Pretty-prints a JavaScript object or value as formatted JSON for readability.
- **XML to JSON conversion**  
  - Converts XML input to JSON format using the `xml-js` library.
- **Trigger Workflow**  
  - Triggers another Pipedream workflow within the same workspace.
- **Send to Amazon S3**  
  - Sends data to Amazon S3 via Pipedream’s S3 destination integration.  
  - Uses existing Pipedream destination configuration (see Pipedream S3 destination docs).
- **Send email with Nodemailer**  
  - Sends emails via the `nodemailer` Node.js package.  
  - Useful for transactional or notification emails within automations.
- **Pipedream Task Scheduler – Schedule Task**  
  - Schedules a task to run in the future using an existing task scheduler source.  
  - Works with Pipedream’s task scheduler sources for delayed or scheduled execution.
- **Retrieve New RSS Stories**  
  - Fetches only new items from an RSS feed that have not yet been processed.  
  - Helps avoid duplicate processing of feed items.
- **Retrieve All RSS Stories**  
  - Retrieves all stories from one or more RSS feeds.

### Text & Data Formatting
- **[Text] Encode URL**  
  - Encodes a string as a URL-safe value.
- **[Text] Decode URL**  
  - Decodes a previously URL-encoded string.
- **[Text] Trim Whitespace**  
  - Removes leading and trailing whitespace from text.
- **[Text] Transform Case**  
  - Changes the casing of text (e.g., upper/lower/title case, depending on configuration in the action).
- **[Text] Split Text**  
  - Splits text on a specified character or word.  
  - Can return a single segment or all segments.
- **[Text] Set Default Value**  
  - Returns a default value when the input text is empty.

> Note: The product exposes a total of 48 actions; only the ones explicitly listed in the provided content are detailed here.

## Pricing
No pricing information is provided in the supplied content for Pipedream Utils MCP Server. Pricing may follow Pipedream’s general platform pricing and would need to be confirmed on the main Pipedream website or account billing pages.