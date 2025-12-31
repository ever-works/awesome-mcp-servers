# DeployHQ MCP Server

**Category:** Code Execution & Automation MCP Servers  
**Slug:** `deployhq-mcp-server`

## Description
The DeployHQ MCP Server is an MCP-compatible service that lets MCP clients automate code deployments using DeployHQ. It supports deploying projects from Git, Subversion (SVN), and Mercurial repositories through DeployHQ’s deployment platform.

## Features
- **MCP-compatible deployment server**
  - Exposes DeployHQ deployment capabilities to any MCP client.
  - Uses a single static MCP server URL for all supported clients.

- **Repository support**
  - Automates deployments from:
    - Git repositories
    - Subversion (SVN) repositories
    - Mercurial (Hg) repositories

- **DeployHQ integration**
  - Connects to an existing DeployHQ account.
  - Uses DeployHQ as the underlying deployment service for projects.

- **Unified server endpoint**
  - Static MCP server URL for configuration: `https://mcp.pipedream.net/v2`.
  - Authentication is handled when adding the server in the client application.

- **Client-agnostic setup**
  - Designed to be added to different MCP-compatible chat or AI clients.
  - Configuration instructions are provided per client type via the configuration page.

## Configuration
- Connect a DeployHQ account through the Pipedream interface.
- Copy and use the static MCP server URL: `https://mcp.pipedream.net/v2` when adding the server to an MCP client.
- Complete authentication within the client during server setup.

## Pricing
Pricing details are not provided in the available content.