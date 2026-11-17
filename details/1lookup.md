# 1Lookup

Hosted MCP server that lets Claude, Cursor and other AI agents validate phone numbers, emails and IPs: add one URL, sign in, no API key to paste.

## Basic Info

- **Name:** 1Lookup
- **Category:** Data Access Integration MCP Servers
- **Brand:** 1Lookup
- **Source URL:** https://www.1lookup.io/
- **MCP Endpoint:** `https://app.1lookup.io/api/mcp`
- **Product Page:** https://www.1lookup.io/products/mcp
- **Tags:** `validation`, `data-validation`, `verification`, `ip-lookup`, `geolocation`, `risk-scoring`, `oauth`, `remote`, `hosted`

## Features

- `validate_phone`: checks that a phone number is real and active, with line type, carrier, DNC status and a fraud/risk score.
- `verify_email`: checks that an address exists and is deliverable, and flags disposable, role-based and risky addresses.
- `ip_lookup`: geolocation, connection type and proxy/VPN/Tor/datacenter flags with a fraud/risk score.
- `bulk_verify`: validates up to 50 phones, emails or IPs in one call.
- `get_account`: returns the plan and remaining credits (free, spends no credits).

## Setup & Configuration

- Add `https://app.1lookup.io/api/mcp` as a remote MCP server (streamable HTTP) in Claude, Cursor or any remote MCP client.
- Sign in and approve access with OAuth 2.1 (PKCE); no API key to paste.
- Tool calls use the same credits as the 1Lookup REST API (1 credit per phone, email or IP).
- Requires a paid 1Lookup plan; a 7-day trial is available. Free-plan accounts get `403 UPGRADE_REQUIRED`.
