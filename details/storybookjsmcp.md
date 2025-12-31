# storybookjs/mcp

**Category:** Testing & Debugging Tools  
**Brand:** Storybook  
**Source:** https://github.com/storybookjs/mcp

## Overview
storybookjs/mcp is an open-source MCP (Model Context Protocol) server from the Storybook team that lets AI agents automatically write and test stories for UI components. It integrates Storybook-driven UI development workflows with MCP-compatible AI tooling.

## Features
- **MCP Server for Storybook**  
  - Implements a Model Context Protocol server specifically tailored to Storybook-based projects.  
  - Exposes Storybook-related capabilities to MCP-compatible AI agents.

- **AI-assisted Story Authoring**  
  - Enables AI agents to generate Storybook stories for existing UI components.  
  - Automates boilerplate story creation and repetitive configuration work.

- **Automated Story Testing**  
  - Provides tools for AI agents to run and validate stories against components.  
  - Supports iterative refinement of stories based on test outcomes.

- **Integration with Storybook Workflows**  
  - Designed to fit into Storybook-driven UI development practices.  
  - Works alongside an existing Storybook instance (e.g., via the `apps/internal-storybook` setup in the repo).  
  - Uses project configuration files (e.g., `.mcp.json`, `.mcp.inspect.json`) to define how the MCP server interacts with the codebase.

- **Monorepo / Workspace Setup**  
  - Organized as a PNPM workspace with a `packages` directory for modular components of the MCP server.  
  - Shared TypeScript configuration via `tsconfig.json` and `tsdown-shared.config.ts` for consistent builds.

- **Developer Tooling**  
  - Repository includes configuration for VS Code (`.vscode`), linting (`.oxlintrc.json`), formatting (`.prettierrc`, `.prettierignore`), and Node version management (`.nvmrc`).  
  - Uses changesets (`.changeset`) for versioning and release management.

- **Open Source Licensing**  
  - Distributed under the license specified in the `LICENSE` file in the repository (see repo for exact terms).

## Pricing
- No pricing information is provided; the project appears to be an open-source GitHub repository. Consult the `LICENSE` file for usage and distribution terms.
