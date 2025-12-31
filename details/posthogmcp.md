# PostHog MCP

**Category:** Business & Commerce – MCP Servers  
**Slug:** posthogmcp  
**Brand:** PostHog  
**Source:** https://github.com/PostHog/mcp

## Overview

PostHog MCP is the official Model Context Protocol (MCP) server for integrating PostHog with AI agents and compatible developer tools. It allows agents and editors to interact with PostHog’s analytics stack (product analytics, feature flags, error tracking, etc.) via MCP tools. The server has been moved into the PostHog monorepo and is now maintained there.

Main documentation: https://posthog.com/docs/model-context-protocol

## Features

- **Official PostHog MCP implementation**  
  - Maintained by PostHog as the canonical MCP server for the PostHog platform.

- **Integration with MCP‑compatible tools**  
  - Usable from tools that support MCP, including:  
    - Cursor  
    - Claude  
    - Claude Code  
    - VS Code  
    - Zed

- **Wizard‑based setup**  
  - One‑command installation and configuration via:  
    - `npx @posthog/wizard@latest mcp add`

- **Multi‑language implementation structure**  
  - Repository (now mirrored in the monorepo) contains/contained language‑specific implementations and schemas:  
    - `typescript/`  
    - `python/`  
    - `schema/` (shared MCP schema definitions)  
    - `examples/` (usage examples)

- **Containerization support**  
  - `Dockerfile` for building and running the MCP server in containerized environments.

- **Editor & tooling configuration**  
  - `.vscode/` configuration for local development and integration.  
  - `.husky/` hooks and `biome.json` for code quality/formatting workflows.  
  - GitHub Actions under `.github/workflows` for CI/CD and automated releases.

- **Automated release configuration**  
  - `package.json` and release‑please config files (`.release-please-config.json`, `.release-please-manifest.json`) for managing versioning and publishing.

- **Open‑source licensing & policies**  
  - Distributed under an open‑source license (see `LICENSE` in the repo).  
  - Includes project governance files such as a code of conduct and security policy.

## Installation & Usage

- Install into supported MCP clients with:

  ```bash
  npx @posthog/wizard@latest mcp add
  ```

- For current source and usage details, refer to the PostHog monorepo location:  
  https://github.com/PostHog/posthog/tree/master/products/mcp

## Pricing

- No pricing information is provided in the available content. The project appears as an open‑source MCP server hosted on GitHub; consult PostHog’s main site or documentation for any associated platform pricing.
