# Commune MCP

**Brand:** Commune
**Category:** Communication & Email MCP Servers
**Tags:** email, agent, inbox, communication, sms, structured-extraction, custom-domain

## Overview
Commune MCP is email infrastructure for AI agents. Unlike wrappers around Gmail or SMTP, it's built from the ground up for programmatic use — agents can create inboxes, send and receive email, manage concurrent threads, and extract structured data from inbound mail without parsing raw text.

## Features
- **Programmatic inbox creation** — spin up an inbox per agent, customer, or workflow on demand
- **Send & receive email** — full two-way email with proper thread tracking
- **Thread management** — keeps concurrent conversations isolated so the agent doesn't mix up replies
- **Custom domains** — send from your own domain, not a generic shared sender
- **Structured extraction** — inbound emails parsed into structured data automatically
- **Attachment support** — upload and download file attachments
- **SMS** — send and receive SMS from the same server
- **Built-in deliverability** — not SMTP; designed so agent emails don't land in spam

## Technical Details
- **Runtime:** Python, installed via `uvx commune-mcp` (no global install needed)
- **Auth:** `COMMUNE_API_KEY` environment variable
- **Protocol:** Model Context Protocol (MCP) via stdio
- **Version:** 0.1.7 (production-ready)

## Getting Started
```json
{
  "mcpServers": {
    "commune": {
      "command": "uvx",
      "args": ["commune-mcp"],
      "env": { "COMMUNE_API_KEY": "comm_..." }
    }
  }
}
```
Get an API key at [commune.email](https://commune.email). Full setup docs at [docs.commune.email](https://docs.commune.email).

## Links
- **GitHub:** https://github.com/commune-sh/commune-mcp
- **PyPI:** https://pypi.org/project/commune-mcp/
- **Website:** https://commune.email
- **Documentation:** https://docs.commune.email

## Pricing
Free tier available. See [commune.email](https://commune.email) for current plans.
