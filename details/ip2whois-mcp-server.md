# IP2WHOIS MCP Server

**Category:** Data Access & Integration – MCP Servers  
**Brand:** ip2whois  
**Slug:** `ip2whois-mcp-server`

IP2WHOIS MCP Server is an MCP-compatible wrapper around the IP2WHOIS WHOIS lookup API, allowing tools and applications to programmatically retrieve structured domain registration and WHOIS data using a unified MCP server endpoint.

---

## Features

### WHOIS Lookup Action
- Single WHOIS lookup action exposed as an MCP tool.  
- Retrieves structured WHOIS and domain registration information using a domain name.
- Returns comprehensive WHOIS data, including (when available):
  - Domain creation date
  - Last updated date
  - Expiration date
  - Domain age
  - Registrant contact information
  - Mailing address
  - Phone number
  - Email address
  - Nameservers used by the domain
  - Additional WHOIS fields as documented in the IP2WHOIS API.
- Supports queries across:
  - 1113 TLDs
  - 634 ccTLDs

### MCP Server Integration
- Exposed via a static MCP server URL: `https://mcp.pipedream.net/v2`.
- Works with any MCP-compatible client; authentication is handled when adding the server to the application.
- Can be added to various chat or agent clients that support MCP for programmatic domain info lookups.

---

## Configuration
- Connect an IP2WHOIS account through Pipedream to use the MCP server.
- Add the static MCP server URL to your MCP-compatible client.
- Detailed configuration steps are available on the referenced configuration page (client-specific instructions for adding the server).

---

## Pricing
- No pricing details are provided in the available content. Refer to the IP2WHOIS or Pipedream websites for up-to-date pricing information.