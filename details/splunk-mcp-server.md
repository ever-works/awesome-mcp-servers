# Splunk MCP Server

**Category:** Monitoring  
**Tags:** Observability, Logs, Security  
**Website:** https://mcp.pipedream.com/app/splunk

## Description
Splunk MCP Server is an MCP (Model Context Protocol) server that connects MCP-compatible tools and chat clients to Splunk. It enables running searches, tracking search jobs, and sending events to Splunk from applications or AI assistants, providing visibility and insights across organizational data for security, reliability, and operations analytics.

## Features

### MCP Server Integration
- Provides a static MCP server URL usable by any compatible client:  
  `https://mcp.pipedream.net/v2`
- Designed to be added as a server to chat-based and other MCP-enabled applications (e.g., ChatGPT / OpenAI clients).
- Authentication handled when adding/configuring the server in the client application.

### Splunk Connectivity
- Connects an MCP client to a Splunk account to access data and analytics capabilities.
- Supports configuration of Splunk connection through Pipedream (sign-in and account management).

### Available Tools (Actions)
1. **Run Search**  
   - Executes a Splunk search query.  
   - Returns search results to the calling client.  
   - Suitable for querying logs, security events, performance data, and other indexed Splunk data.

2. **Get Search Job Status**  
   - Retrieves the status of a previously executed Splunk search job.  
   - Allows checking whether a search is running, completed, or failed, and managing long-running or asynchronous search operations.

3. **Create Event**  
   - Sends a new event to a specified Splunk index.  
   - Enables programmatic ingestion of custom events, logs, or metrics from MCP clients into Splunk.

### Usage & Configuration
- Single shared MCP endpoint for all clients; each client authenticates separately. 
- Guides available for specific chat clients (e.g., ChatGPT / OpenAI) via the configuration documentation on Pipedream.

## Pricing
Pricing information is not provided in the available content. Refer to the Splunk MCP Server page on Pipedream for current pricing or plan details.