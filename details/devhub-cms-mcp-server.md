# DevHub CMS MCP Server

**Category:** content-management-mcp-servers  
**Slug:** devhub-cms-mcp-server  
**Brand:** devhub

## Overview
DevHub CMS MCP Server is a Model Context Protocol (MCP) integration that allows AI agents and MCP-compatible tools (such as Claude Desktop) to interact programmatically with content stored in the DevHub CMS platform. It exposes DevHub CMS functionality as an MCP server so content can be managed and utilized directly from within AI workflows.

- **Type:** Open-source MCP server / developer integration
- **Primary use case:** Programmatic content management and retrieval from DevHub CMS via MCP
- **Repository:** https://github.com/devhub/devhub-cms-mcp

## Features
- **Model Context Protocol (MCP) integration**  
  - Implements an MCP server compatible with MCP clients such as Claude Desktop.  
  - Enables AI agents to call DevHub CMS operations through standardized MCP tooling.

- **DevHub CMS connectivity**  
  - Connects to the DevHub CMS platform using DevHub API credentials.  
  - Uses `DEVHUB_API_KEY` and `DEVHUB_API_SECRET` environment variables for authentication.  
  - Designed specifically for managing content within DevHub-driven websites.

- **Content management via AI tools**  
  - Provides programmatic access to website content (e.g., reading and managing content entries) from AI assistants.  
  - Intended to let agents "manage content in the DevHub CMS system" directly from MCP-compatible environments.  
  - Suitable for workflows like content updates, content querying, and structured content operations through AI.

- **Claude Desktop integration**  
  - Can be configured as an MCP server in Claude Desktop by adding a `devhub_cms_mcp` entry to the `mcpServers` section of `claude_desktop_config.json`.  
  - Uses `command: "uvx"` with `args: ["devhub-cms-mcp"]` for launching the server.

- **uv-based distribution**  
  - Distributed as a Python/uv package and launched via the `uvx` command.  
  - Requires the `uv` package manager installed on the local system.

- **Containerization support**  
  - Includes a `Dockerfile` for running the MCP server in a containerized environment.

- **Python project setup**  
  - Managed via `pyproject.toml` and `uv.lock` for reproducible Python environments.  
  - Organized source code under `src/devhub_cms_mcp` with automated tests under `tests`.

## Installation & Configuration (technical summary)
- **Prerequisites**  
  - `uv` package manager installed locally.  
  - DevHub CMS API key and secret.

- **Basic usage pattern**  
  - Run via `uvx devhub-cms-mcp` (as configured in Claude Desktop).  
  - Set environment variables `DEVHUB_API_KEY` and `DEVHUB_API_SECRET` for CMS access.  
  - Register the server in MCP-compatible clients using the provided command and args.

## Pricing
No pricing information is provided in the available content. The project appears as an open-source GitHub repository; any DevHub CMS platform costs or licensing are not described in the referenced content.
