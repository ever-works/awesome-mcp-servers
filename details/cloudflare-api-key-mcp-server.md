# Cloudflare (API key) MCP Server

## Overview
The Cloudflare (API key) MCP Server is an MCP-compatible integration for interacting with Cloudflare’s API using an API key. It enables tools and workflows to programmatically manage Cloudflare resources for CDN, DNS, Internet security, and DDoS-related configurations.

- **Category:** Cloud & DevOps MCP Servers  
- **Provider/Brand:** Cloudflare (via Pipedream MCP)  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Authentication:** Cloudflare API key

## Features

### MCP Integration
- Static MCP server URL usable with multiple MCP-compatible chat/agent clients.
- Authentication handled when adding the server to your MCP application.
- Exposes Cloudflare operations as MCP tools (actions) for use in automations and assistants.
- Currently provides **19 actions** as tools (subset listed below from the available content).

### CDN & Caching Management
- **Purge Files by URL**  
  - Granularly remove one or more files from Cloudflare’s cache by specifying URLs.
- **Purge All Files**  
  - Remove all cached files from Cloudflare’s cache for a zone.

### DNS Management
- **Patch DNS Record**  
  - Partially update (patch) a DNS record for a specific zone.
- **List DNS Records**  
  - List, search, sort, and filter DNS records within a zone.
- **Import DNS Records**  
  - Import DNS records into a zone from a BIND configuration.
- **Export DNS Records**  
  - Export DNS records from a zone to a BIND configuration.
- **Delete DNS Record**  
  - Delete an existing DNS record in a zone.

### Zone & Security Management
- **Update Zone Security Level**  
  - Set the security profile for a website/zone, automatically adjusting underlying security settings.
- **Create Zone**  
  - Programmatically create a new Cloudflare zone.
- **Create IP Access Rule**  
  - Create an IP access rule at the account level, applied to all zones in the account.

### Certificates & TLS
- **List Certificates**  
  - List all existing Origin CA certificates for a given zone.
- **Revoke Certificate**  
  - Revoke an Origin CA certificate by its serial number.

### Workers KV / Key-Value Storage
- **Create Namespace**  
  - Create a new Workers KV namespace within an account.
- **Create Key/Value Pairs**  
  - Create new key/value entries in a specified Workers KV namespace.

*(Note: The page states there are 19 available actions; only the actions present in the provided content are listed here.)*

## Pricing
No pricing information is provided in the available content. Usage may depend on both Cloudflare account pricing and any terms associated with Pipedream’s MCP infrastructure.
