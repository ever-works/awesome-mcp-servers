# Netlify MCP Server

## Overview
Netlify MCP Server is an official Netlify implementation of the Model Context Protocol (MCP) that allows AI/code agents to interact with Netlify’s development and deployment platform. Through this server, agents can use Netlify’s API and CLI capabilities to create, build, deploy, and manage Netlify projects and resources using natural language prompts.

- **Type**: MCP server (integration for AI/code agents)
- **Vendor**: Netlify
- **Category**: Cloud / DevOps MCP servers
- **Repository**: https://github.com/netlify/netlify-mcp
- **MCP endpoint**: https://netlify-mcp.netlify.app/mcp
- **Auth**: OAuth 2.1

## Features
- **MCP-compliant server**  
  - Implements the Model Context Protocol to connect with compatible AI/code agents.
  - Exposes Netlify functionality as MCP tools for use inside AI environments.

- **Netlify API & CLI integration**  
  - Enables agents to call Netlify APIs programmatically via MCP.  
  - Integrates with Netlify CLI behaviors so agents can perform common developer workflows.

- **Project lifecycle management via natural language**  
  - Create new Netlify projects from within an AI agent.  
  - Build and deploy sites and apps programmatically.  
  - Manage existing Netlify resources (sites, configurations, etc.) by describing desired actions in natural language.

- **Hosted MCP endpoint**  
  - Public MCP endpoint at `https://netlify-mcp.netlify.app/mcp` suitable for configuration in MCP-compatible clients.

- **OAuth 2.1 authentication**  
  - Uses OAuth 2.1 to authorize access to a user’s Netlify account and resources.  
  - Ensures agent actions are performed under the authenticated user’s permissions.

- **TypeScript / Node.js implementation**  
  - Source includes TypeScript entry (`netlify-mcp.ts`) and configuration (`tsconfig.json`).  
  - Distributed as an npm-based project (`package.json`, `package-lock.json`).

- **Netlify-native project configuration**  
  - Includes `netlify.toml` for first-class deployment and configuration on Netlify’s platform.

- **Extensible codebase**  
  - Organized source under `src/` and `netlify/` directories for adding or customizing MCP tools.
  - Contribution guidelines provided via `CONTRIBUTING.md`.

## Pricing
No pricing information is provided in the available content. The project is hosted on GitHub; licensing and cost (if any) would need to be confirmed in the repository’s license or Netlify documentation.