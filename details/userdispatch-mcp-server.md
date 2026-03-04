# UserDispatch MCP Server

**Category:** Business & Commerce MCP Servers
**Brand:** UserDispatch
**Source:** https://github.com/kiruna-labs/userdispatch-mcp

## Overview
UserDispatch MCP Server is a cloud-hosted MCP server for collecting and managing user feedback directly from AI coding agents. It pairs an embeddable feedback widget (bug reports, ratings, questions) with a full MCP server that exposes tools for submission triage, email reply drafting, and weekly digest generation.

## Features
- **Embeddable feedback widget**
  - Drop-in `<script>` tag for any web app
  - Captures bug reports, feature requests, ratings, and questions
  - Framework auto-detection (Next.js, Vite, Nuxt, SvelteKit, Astro, static HTML)

- **5 MCP tools**
  - `submissions` — list, view, reply, update status, delete submissions
  - `apps` — create and manage feedback apps
  - `stats` — submission counts and trends
  - `org` — organization settings
  - `members` — team member management

- **5 MCP resources**
  - Recent submissions, submission detail, stats overview, apps list, org overview

- **2 MCP prompts**
  - `triage-submissions` — review and categorize new submissions
  - `weekly-digest` — 7-day feedback summary

- **Streamable HTTP transport**
  - Single endpoint: `https://userdispatch.com/api/mcp`
  - Bearer token authentication (`ud_` prefixed tokens)

- **One-line install**
  - `npx userdispatch init` — CLI handles widget injection + MCP config

## Usage
1. Run `npx userdispatch init` in your project
2. Sign in via Google OAuth and configure your app
3. The CLI injects the widget and configures your MCP client
4. Use MCP tools to triage feedback, draft replies, and track trends

## Pricing
Free tier available. See https://userdispatch.com for details.
