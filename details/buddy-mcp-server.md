# Buddy MCP Server

**Category:** Cloud & DevOps MCP Servers  
**Brand:** Buddy  
**Website:** https://buddy.works/docs/ai-agents/mcp  
**MCP Endpoint:** `https://mcp.buddy.works/mcp`

A remote Model Context Protocol (MCP) server that connects coding agents to a Buddy workspace. It has over 90 tools for CI/CD pipelines, sandboxes, packages, domains and test suites. Buddy hosts it in three regions, and the `bdy` CLI can proxy it locally over stdio.

---

## Features

### Endpoints
- US: `https://mcp.buddy.works/mcp`
- EU: `https://mcp.eu.buddy.works/mcp`
- Asia: `https://mcp.asia.buddy.works/mcp`
- Local: `bdy mcp` runs a stdio server that proxies to the remote one.

### Authentication
- Interactive OAuth: no credentials in the config, browser login on first use.
- Personal access token sent as a Bearer header, for headless use.
- An existing Buddy CLI session (`npm install -g bdy`, then `bdy login`).

### Tool Categories
- User, workspaces, projects and members
- Pipelines: CI/CD pipelines, runs and actions
- Source
- Targets
- Sandboxes
- Packages
- Domains and distros
- Suites: visual and unit tests

### Integration with AI Tools
- Claude Code: `claude mcp add --transport http buddy https://mcp.buddy.works/mcp`
- Cursor, with OAuth
- Codex and Grok, through `bdy mcp`
- `bdy mcp --tools pipelines,source` limits the server to the listed tool categories.

### Limitations
- Some operations are irreversible, for example deleting a project, tearing down a sandbox or removing a domain.

---

## Use Cases
- Run a pipeline from a coding agent and read the build output and logs.
- Create and manage cloud sandboxes from an agent session.
- Review visual and unit test suites.
- Manage domains and distros for deployed apps.

---

## Pricing

The MCP server needs a Buddy account. Buddy has a Free plan (1 seat, 2 concurrent runs, $1 of usage credit per month) and paid Pro and Team plans. Details: https://buddy.works/pricing
