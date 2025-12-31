# Clearbit MCP Server

**Category:** Business & Commerce – MCP Servers  
**Brand:** Clearbit  
**Source:** https://mcp.pipedream.com/app/clearbit

B2B lead data enrichment, qualification, and scoring via a Clearbit integration exposed through the Model Context Protocol (MCP), provided by Pipedream.

![Clearbit](https://clearbit.com/assets/images/screens/enrichment.png)

---

## Overview

Clearbit MCP Server is an MCP-compatible integration that connects Clearbit’s B2B data services to MCP-enabled applications. It lets you enrich, qualify, and score leads by querying Clearbit’s person and company datasets directly from your chat or agent client.

---

## Features

### MCP Server Integration
- Static MCP server URL: `https://mcp.pipedream.net/v2` (shared across clients).  
- Connects Clearbit’s APIs to any MCP-compatible chat or agent application.  
- Authentication is handled when adding the server to your application.  
- Works after you sign in and connect your Clearbit account via Pipedream.

### Available Tools (Actions)
The server exposes 5 Clearbit actions as MCP tools:

1. **Find Contacts**  
   - Find people who work at a specific company.  
   - Uses Clearbit’s person / contact data to return individuals at a given company.

2. **Find Companies**  
   - Discover companies based on specific criteria.  
   - Supports searching organizations using filters (e.g., attributes like size, industry, etc. as supported by Clearbit’s underlying API).

3. **Email Lookup**  
   - Retrieve a person by email address.  
   - Returns enriched profile data for a given email using Clearbit’s Person API.

4. **Domain Lookup**  
   - Look up a company by its domain (Company API).  
   - Returns enriched company data (e.g., firmographic information) associated with the domain.

5. **Company Name to Domain**  
   - Convert an exact company name into a website domain.  
   - Also returns the company logo along with the domain where available.

### Use Cases
- B2B lead enrichment for sales and marketing workflows.  
- Lead qualification and scoring using company and contact attributes.  
- Building MCP-based agents that can look up and enrich leads directly in chat.

### Configuration & Client Integration
- Single static server URL used across all MCP clients.  
- Per-client authentication occurs when adding the server to your app.  
- Client-specific setup instructions available via the configuration page linked from the app.

---

## Pricing

No pricing information is provided in the supplied content. Use of this MCP server likely depends on your Clearbit and/or Pipedream account plans; refer to their respective pricing pages for details.