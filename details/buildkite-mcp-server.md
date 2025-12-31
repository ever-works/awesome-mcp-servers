# Buildkite MCP Server

**Category:** Cloud & DevOps MCP Servers  
**Brand:** Buildkite  
**Website:** https://buildkite.com/docs/apis/mcp-server  
**MCP Endpoint:** `https://mcp.buildkite.com/mcp`

An open-source Model Context Protocol (MCP) server that exposes Buildkite CI/CD data (pipelines, builds, jobs, and Test Engine test data) to AI tools, agents, and editors via the Buildkite REST API. It supports both remote (hosted) and local (self-hosted) modes and uses OAuth 2.1 for secure access in the remote configuration.

---

## Features

### General Capabilities
- Implements the Model Context Protocol (MCP) to connect AI tools, agents, and editors to Buildkite.
- Exposes Buildkite product data, including:
  - Pipelines
  - Builds
  - Jobs
  - Test Engine test data
- Built on top of the Buildkite REST API.
- Open-source server implementation (available on GitHub).
- Provides a set of **MCP tools** for interacting with Buildkite resources (see tools documentation for full list).

### Server Types

#### Remote MCP Server (Hosted by Buildkite)
- Hosted by Buildkite at `https://mcp.buildkite.com/mcp`.
- Recommended option for most users and interactive AI tools.
- Typically used from AI tools you interact with directly via a prompt.
- Automatically updated by Buildkite, providing new features and fixes without local installs or upgrades.

##### Authentication & Authorization (Remote)
- Uses OAuth 2.1 via your Buildkite user account.
- Buildkite issues short-lived OAuth access tokens that:
  - Represent your user account.
  - Include pre-set **read** and **write** permission scopes for the server.
- Token lifetimes:
  - Access tokens valid for 12 hours.
  - Refresh tokens valid for 7 days.
- OAuth flow runs after configuring your AI tool to connect to the remote MCP server.

##### Security & Convenience
- No API access token configuration required (reduces risk of token leakage).
- Suitable for **personal** and **interactive** usage with AI tools.

##### Limitations
- Not suitable for **automated workflows** where:
  - A fixed MCP server version is required.
  - Strict version reproducibility and consistency are important.

##### Read-only Remote MCP Server
- Separate remote variant offering **read-only** access.
- Intended for users who prefer not to grant write permissions while using the MCP server.

#### Local MCP Server (Self-hosted)
- Run the MCP server locally in your own environment.
- Requires installation of the MCP server package.
- Requires manual configuration of a Buildkite API access token for authentication.
- Appropriate when you need:
  - Control over the specific server version.
  - Use in automated workflows and CI automation.
  - Tighter control over environment and upgrade cadence.

##### Local Setup Steps (Conceptual)
- Install and run the Buildkite MCP server locally.
- Configure a Buildkite API access token for the server.
- Configure your AI tools to connect to the local MCP endpoint.

### Integration with AI Tools
- Both remote and local modes can be used by MCP-compatible tools, editors, and agents.
- Separate configuration flows described for:
  - Remote MCP server integration.
  - Local MCP server integration.

---

## Use Cases
- Query and explore Buildkite pipelines and builds from AI-powered chat or editor integrations.
- Inspect jobs and test data (including Test Engine results) via AI tools.
- Automate or assist CI/CD tasks interactively through MCP-compatible agents.
- Read-only observability into Buildkite resources when using the dedicated read-only remote server.

---

## Pricing

No pricing information is provided in the available content for the Buildkite MCP Server itself. It is described as an open-source server and a hosted endpoint, but specific pricing or plans (if any) are not detailed here.