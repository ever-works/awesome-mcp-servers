# Clearout MCP Server

## Overview
Clearout MCP Server is an MCP (Model Context Protocol) server that exposes Clearout’s email verification and email finder capabilities for use within MCP-compatible clients. It supports both bulk and real-time use cases via a single shared endpoint.

- **Name:** Clearout MCP Server  
- **Category:** Business & Commerce – MCP Servers  
- **Provider / Brand:** Clearout (via Pipedream Connect)  
- **Description:** MCP server that provides model-context access to Clearout’s email verification and email finder tools.

## Features
- **Email verification**  
  - Validate email addresses to check if they are valid and deliverable.  
  - Suitable for both bulk list verification and real-time (single) checks.

- **Email finder**  
  - Find email addresses (lead/contact discovery) for use in enrichment workflows.  
  - Supports real-time lookups and bulk finding.

- **Bulk operations**  
  - Process multiple emails at once for verification or finding, enabling list-cleaning and enrichment at scale.

- **Real-time operations**  
  - Verify or find emails on-demand for live workflows (e.g., form submissions, lead capture, or interactive tools).

- **Standard MCP endpoint**  
  - Single static MCP server URL for all clients:  
    `https://mcp.pipedream.net/v2`  
  - Authentication is performed when adding the server to your MCP-compatible application.

- **Client-agnostic integration**  
  - Works with any MCP-aware chat client or tool that can register the MCP server URL.  
  - Configuration guidance available via the generic MCP configuration documentation.

## Integration / Setup
- **MCP server URL:** `https://mcp.pipedream.net/v2`  
- **Usage pattern:**  
  1. Add the MCP server URL to your MCP-compatible app.  
  2. Authenticate when prompted by your client.  
  3. Call tools for email verification or email finding in real time or in bulk.

## Pricing
- Not specified on the provided page. No plan or pricing details are included in the available content.
