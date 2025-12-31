# BitBucket MCP Server

## Overview
BitBucket MCP Server is an MCP server for Bitbucket Cloud that allows MCP-based agents and tools to interact with Bitbucket repositories, pull requests, and CI/CD workflows through Bitbucket’s APIs.

- **Category:** Development Tools – MCP Servers  
- **Vendor / Brand:** Atlassian  
- **Works with:** Bitbucket Cloud  
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`

## Features
- **Bitbucket Cloud integration**  
  - Connects MCP-compatible clients to Bitbucket Cloud.  
  - Uses Bitbucket’s APIs to expose repository and workflow functionality.

- **Repository access**  
  - Access Bitbucket Git repositories via MCP for reading and managing code (based on Bitbucket API capabilities and configured permissions).

- **Pull request operations**  
  - Work with pull requests through MCP (e.g., listing and inspecting PRs via Bitbucket APIs, subject to permissions and client support).

- **CI/CD workflows**  
  - Integrates with Bitbucket CI/CD (pipelines) so MCP-based agents can interact with workflows through Bitbucket’s APIs.

- **Static MCP server URL**  
  - Uses a single static server URL for all clients: `https://mcp.pipedream.net/v2`.  
  - Authentication occurs when adding the server to the MCP-compatible application.

- **Client-agnostic configuration**  
  - Designed to be added to various MCP-enabled chat or agent clients using the same base URL.  
  - Additional configuration details are available via the provider’s configuration documentation.

## Tags
- git  
- repository-management  
- cicd

## Pricing
The provided content does not specify any pricing or plans for BitBucket MCP Server.