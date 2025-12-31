# Lusha MCP Server

## Overview
Lusha MCP Server exposes Lusha’s B2B lead enrichment and contact data services as an MCP server, enabling programmatic enrichment of business leads from within compatible chat or agent clients using a single static MCP endpoint.

- **Category:** Business & Commerce – MCP Servers  
- **Use cases:** B2B lead enrichment, sales prospecting, CRM workflows, contact and company research
- **MCP server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL that works for all clients, with authentication handled when adding the server to your application.
- Designed to integrate with chat clients and applications that support the MCP (Model Context Protocol).

### Lead & Contact Enrichment Tools (Actions)
The server exposes Lusha’s API as MCP tools (15 actions in total). The documented ones include:

1. **Search Single Contact**  
   - Search for a single contact using various filters (e.g., role, company, location, and other Lusha-supported filters).  
   - Returns detailed contact data suitable for enrichment in CRM or sales workflows.

2. **Search Single Company**  
   - Search for a single company using various filters (e.g., name, domain, size, industry, and other Lusha-supported filters).  
   - Returns company-level information for account research and targeting.

3. **Search Contact Signals**  
   - Search for contact signals using identifiers such as:  
     - LinkedIn URL  
     - Email  
     - Name + company  
   - Combines search and signal enrichment in a single request to return recent activities and intent-like signals about a contact.

4. **Search Company Signals**  
   - Search for company signals using identifiers such as:  
     - Company domain name  
     - Company name  
   - Combines search and signal enrichment in a single request to return recent activities and signals related to a company.

5. **Search and Enrich Contacts**  
   - Search for multiple contacts and simultaneously enrich them with Lusha’s data.  
   - Suitable for bulk lead generation and enrichment workflows.

6. **Search and Enrich Companies**  
   - Search for companies and enrich them with additional firmographic and related data.  
   - Useful for account list building and enrichment.

7. **Get Signal Options**  
   - Retrieve available signal options for a specific entity type:  
     - Contact  
     - Company  
   - Returns the list of signal types that can be used as filters when enriching contacts or companies.

8. **Get Contact Signals By IDs**  
   - Retrieve signals data for a list of contact IDs (up to 100 contacts per request).  
   - Provides recent activities and signals for each specified contact.

9. **Get Contact Recommendations**  
   - Fetch recommended contacts based on given contact IDs.  
   - Returns similar profiles aligned by:  
     - Job title  
     - Seniority  
     - Company context  
   - Supports using a `requestId` to obtain more results from a previous recommendations search.

10. **Get Company Signals By IDs**  
    - Retrieve signals data for a list of company IDs (up to 100 companies per request).  
    - Returns recent activities and signals for targeted companies.

11. **Get Company Recommendations**  
    - Get recommended companies based on a set of input companies.  
    - Supports using a `requestId` to get additional recommendation results from a prior query.

> Note: The interface reports “15 actions available as tools”; only the above actions are explicitly documented in the provided content.

## Pricing
No pricing information is provided in the available content. Pricing may depend on Lusha and/or Pipedream account plans and is not specified here.