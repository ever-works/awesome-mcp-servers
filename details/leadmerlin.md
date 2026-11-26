# LeadMerlin

Local business lead generation for AI agents: search Google Maps businesses by niche and city, then get each one enriched with owner name, emails checked against the mail server, phone line type and website tech.

## Basic Info

- **Name:** LeadMerlin
- **Category:** Business Commerce MCP Servers
- **Source URL:** https://github.com/HalberdLLC/leadmerlin-mcp
- **MCP Endpoint:** `https://api.leadmerlin.com/mcp`
- **Tags:** `lead-generation`, `prospecting`, `sales`, `remote`

## Features

- `find_locations` and `suggest_keywords`: turn a city and a niche into location codes and sharper Google categories.
- `start_search`, `get_job`, `get_results`: search local businesses and page through the enriched results.
- `enrich_domains`: enrich domains you already have.
- Each business carries owner name, emails checked against the mail server, phone line type (mobile / landline / VoIP) and the tech its website runs.
- `check_website_tech`: free, no API key needed.

## Setup

- Add `https://api.leadmerlin.com/mcp` as a remote MCP server (Streamable HTTP) with your API key in the `x-api-key` header.
- Or run the local stdio bridge: `npx -y github:HalberdLLC/leadmerlin-mcp` (Node 18+, no dependencies, MIT).
- Paid tools need an API key; signup gives 100 free leads, no card.
