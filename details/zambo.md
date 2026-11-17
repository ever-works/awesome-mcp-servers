# Zambo

Hosted MCP server with 153 tools behind one endpoint, work handover between AIs, and a verifiable AER-1 receipt for every job.

## Basic Info

- **Name:** Zambo
- **Category:** Security Attestation Mcp Servers
- **Source URL:** https://zambo.dev/mcp
- **MCP Endpoint:** `https://zambo.dev/mcp`
- **Tags:** `verification`, `attestation`, `audit-logs`, `remote`

**The verifiable work layer for AI: 153 tools behind one remote MCP endpoint, continuity across AIs, and a verifiable AER-1 receipt for every job.**

## Features

- **One endpoint, full tool surface:**
  - Streamable HTTP at https://zambo.dev/mcp
  - 153 tools total, 36 on the default surface
  - No install, no credential needed to start

- **Verifiable receipts (AER-1):**
  - Every job closes with an AER-1 receipt proving the saved result was not changed
  - Receipts are checkable at https://zambo.dev/verify/
  - AER-1 is an IETF draft (draft-zambo-aer1-26), with a published conformance corpus of 143 vectors and 146 checks

- **Continuity across AIs:**
  - Work started in one AI can be wrapped into a handover and picked up in another AI
  - Pickup is always free

## Pricing

Free tier: 20 calls and 1 wrap-up free every day. Day Pass: $0.99 USDC on Base for 24 hours of unlimited use, wrap-ups included. Zambo Pass: $29 for 30 days, $290 for 365 days, $19 for $ZAMBO holders (one-time payments, not subscriptions).
