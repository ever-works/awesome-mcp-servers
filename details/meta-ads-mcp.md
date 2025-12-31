# Meta Ads MCP

**Category:** Business & Commerce MCP Servers  
**Brand:** Pipeboard  
**Source:** https://github.com/pipeboard-co/meta-ads-mcp

## Overview
Meta Ads MCP is an MCP server for managing Facebook and Instagram (Meta) advertising accounts. It exposes Meta Ads functionality for programmatic use, enabling automated workflows for analysis, creative testing, and campaign optimization. A hosted instance is available at `https://mcp.pipeboard.co/meta-ads-mcp` using OAuth 2.1 authentication.

## Features
- **Meta Ads management**
  - Interfaces with Facebook and Instagram (Meta) advertising accounts.
  - Supports programmatic control over ads-related resources via MCP.

- **Campaign and workflow automation**
  - Automates common Meta Ads workflows.
  - Enables scripted or tool-driven campaign optimization.

- **Analysis and reporting**
  - Provides programmatic access to performance analysis for Meta campaigns (e.g., metrics and insights exposed via MCP tools).

- **Creative management and testing**
  - Tools for ad creative creation and updates.
  - Supports creative testing workflows.
  - `lead_gen_form_id` parameter support in creative-related functions to link lead-generation creatives with lead forms.

- **Ad campaign optimization**
  - Operations suitable for adjusting and optimizing campaigns programmatically (e.g., budgets, creatives, structures) via MCP tools.

- **MCP integration**
  - Implements the Model Context Protocol (MCP) so AI tools and compatible clients can call Meta Ads operations as tools.
  - Includes example configurations and usage patterns in the `examples` directory.

- **Authentication**
  - Hosted instance uses OAuth 2.1 for secure access.
  - Server and examples use Bearer tokens via the `Authorization` header for API calls.

- **Deployment and usage assets**
  - Example HTTP clients and tests for interacting with the server.
  - GitHub workflows for building and publishing releases.

- **Licensing**
  - Distributed with an open-source license (see `LICENSE` in the repository).

## Pricing
No pricing information is provided. The project is available as an open-source GitHub repository; usage terms for the hosted instance are not specified in the available content.