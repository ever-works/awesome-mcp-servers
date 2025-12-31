# sentry-mcp

**Category:** Monitoring  
**Brand:** Sentry  
**Website:** https://mcp.sentry.dev  
**Source:** https://github.com/getsentry/sentry-mcp

An MCP (Model Context Protocol) server integration that lets LLMs access and work with Sentry.io error tracking and performance monitoring data.

---

## Features

- **MCP Server for Sentry**  
  - Implements a Model Context Protocol server that exposes Sentry data to LLMs.
  - Designed to plug into MCP-compatible LLM runtimes and agents.

- **Sentry Error & Performance Data Access**  
  - Integrates with Sentry.io to surface error tracking data.  
  - Exposes performance monitoring information for analysis and troubleshooting.  
  - Enables LLMs to query application monitoring data programmatically.

- **Tooling & Configuration**  
  - Provides an example `.mcp.json` configuration for quick setup in MCP clients.  
  - Includes an `.env.example` file to illustrate required environment variables (e.g., credentials / project details) for connecting to Sentry.  
  - Organized as a multi-package repository under `packages/` for modular components.

- **Agent Integration Guidance**  
  - `AGENTS.md` describes how to connect the MCP server to various LLM agents or orchestration frameworks.  
  - `CLAUDE.md` contains specific instructions for using sentry-mcp with Claude / Anthropic MCP-compatible tooling.

- **Developer-Oriented Repository Structure**  
  - `docs/` directory with additional documentation and usage patterns.  
  - `bin/` and `scripts/` directories for development, build, or runtime helper scripts.  
  - CI/workflow configuration under `.github/workflows/`.

- **Open Source**  
  - Published as an open-source project on GitHub.  
  - Includes a LICENSE file specifying terms of use and contribution.

---

## Pricing

- Not specified in the provided content.

(Use of sentry-mcp is subject to its open-source license; access to Sentry.io itself may be governed by Sentry’s own pricing and plans, which are not detailed here.)

---

## Tags

- Error tracking  
- Observability  
- Developer tools

---

## Images

- Application monitoring UI: https://sentry.io/_assets/marketing/illustrations/product-ui/application-monitoring.png  
- sentry-mcp illustration: https://github.com/getsentry/sentry-mcp/raw/HEAD/.github/sentry-mcp.png