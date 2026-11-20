# Bugsly

Error tracking that AI coding agents can read over MCP: list and triage issues, read stack traces and AI explanations, and resolve them from your editor. Hosted endpoint with OAuth.

## Basic Info

- **Name:** Bugsly
- **Category:** Monitoring
- **Source URL:** https://bugsly.dev
- **MCP Endpoint:** `https://bugsly.dev/api/mcp`
- **Tags:** `error-tracking`, `monitoring`, `crash-reporting`, `remote`, `oauth`

## Features

- Hosted remote MCP endpoint `https://bugsly.dev/api/mcp`; sign in with OAuth. A local stdio package, `@bugsly/mcp-server`, uses an API token instead.
- Registry name `dev.bugsly/mcp-server`; npm package `@bugsly/mcp-server` 0.5.2.
- Free plan, no card: 1 project, 100 new issues and 50,000 events a month, 7-day retention. Paid plans from $19/month.
- Disclosure: submitted by the Bugsly team.

## Setup

- Add `https://bugsly.dev/api/mcp` as a remote MCP server and sign in; see https://bugsly.dev.
