# Google Calendar MCP Server (nspady)

**Brand:** Google  
**Category:** MCP Server Directories & Lists  
**Source:** https://github.com/nspady/google-calendar-mcp  
**Slug:** `google-calendar-mcp-server-nspady`

## Overview
An open-source MCP (Model Context Protocol) server for integrating Google Calendar into MCP-compatible tools. It enables programmatic management of Google Calendar events, including creating, updating, deleting, and searching for events by attributes such as title and location.

## Features
- **Google Calendar integration via MCP**  
  - Exposes Google Calendar event management as an MCP server for use with MCP-compatible clients and agents.

- **Event lifecycle management**  
  - Create new Google Calendar events.  
  - Update existing events and their attributes.  
  - Delete events from a connected Google Calendar.

- **Event search & filtering**  
  - Search for calendar events by title.  
  - Search and filter events by location.  
  - Supports querying by event attributes (as exposed through the MCP tools).

- **Configuration & setup**  
  - `.env.example` file provided to configure required environment variables (e.g., credentials and settings).  
  - `instructions/` directory for setup and usage guidance.  
  - `docs/` directory for additional documentation.  
  - `examples/` directory showing example configurations or usage.

- **Deployment & operations**  
  - `Dockerfile` for containerized deployment.  
  - `.github/workflows/` for CI/CD or automation workflows.  
  - `scripts/` directory for helper scripts (e.g., development, build, or deployment tasks).

- **Project structure & extensibility**  
  - `src/` directory containing the MCP server implementation.  
  - `future_features/` directory indicating planned or experimental enhancements.  
  - Dedicated files such as `AGENTS.md` and `CLAUDE.md` to document usage with agents and/or Claude-based setups.

- **Release & change tracking**  
  - `CHANGELOG.md` for tracking changes across versions.  
  - `.release-please-manifest.json` to manage automated releases.

## Technical Details
- **Type:** MCP server for Google Calendar event management.  
- **Deployment:** Self-hosted (local or containerized via Docker).  
- **Source code:** Fully available on GitHub.  
- **License:** Open-source (see `LICENSE` file in the repository for exact terms).

## Pricing
- No pricing information is listed in the repository.  
- Distributed as an open-source project under the license specified in the `LICENSE` file; no paid plans are described.