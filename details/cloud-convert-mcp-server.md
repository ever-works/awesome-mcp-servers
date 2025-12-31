# Cloud Convert MCP Server

**Category:** Media Processing MCP Servers  
**Brand:** CloudConvert  
**Type:** MCP server for CloudConvert API-based file conversion

## Overview
Cloud Convert MCP Server is an MCP-compatible service that exposes CloudConvert’s file conversion and related functionality as tools you can use from MCP-enabled chat or development clients. It connects to your CloudConvert account and lets you create and manage conversion jobs, handle file imports, and generate archives via CloudConvert’s API.

## Connection & Configuration
- Uses a static MCP server URL: `https://mcp.pipedream.net/v2`.
- You authenticate when adding the server to your MCP-compatible application.
- Requires connecting your CloudConvert account in order to run conversions and jobs.

## Features

### General
- MCP server interface for CloudConvert’s API.
- Works with multiple MCP clients (chat or other applications).
- Centralized configuration via a single static server URL.

### Available Tools / Actions
The server exposes 6 actions as MCP tools:

1. **Create Job**
   - Creates a new CloudConvert job.
   - Supports one or more tasks in a single job.
   - Suitable for orchestrating multi-step conversion workflows.

2. **Get Task**
   - Retrieves a CloudConvert task by its ID.
   - Enables checking status and details of individual tasks within jobs.

3. **Create Merge Files To PDF Job**
   - Combines multiple input files into a single PDF.
   - Creates a job that produces an export URL for the resulting PDF.
   - Useful for merging documents before sharing or archiving.

4. **Create Import URL Task**
   - Creates a task that imports a file from a given URL into CloudConvert.
   - Allows working with remote files without manual upload.

5. **Create Archive**
   - Creates an archive in a specified format (e.g., ZIP or similar, depending on CloudConvert support).
   - Can bundle multiple files into a single archive as part of a job.

6. **Convert File**
   - Converts an input file to a specified output format using CloudConvert.
   - Leverages CloudConvert’s supported format matrix (documents, media, etc.).
   - Can be integrated into larger jobs or used as a standalone conversion step.

## Pricing
Pricing information is not provided in the available content. Use standard CloudConvert and/or Pipedream billing/pricing documentation to determine any associated costs.