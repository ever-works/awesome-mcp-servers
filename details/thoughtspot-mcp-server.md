# ThoughtSpot MCP Server

**Category:** Data Analysis & Exploration MCP Servers  
**Brand:** ThoughtSpot  
**Website / Endpoint:** `https://agent.thoughtspot.app/mcp`  
**Source Code:** https://github.com/thoughtspot/mcp-server

## Overview

ThoughtSpot MCP Server is a Model Context Protocol (MCP) server that allows AI agents and tools to query and analyze data through ThoughtSpot using OAuth 2.1. It exposes ThoughtSpot’s search and analytics capabilities via an MCP-compatible endpoint, enabling secure, interactive data exploration from agent-based systems.

## Features

- **MCP-compliant server**  
  - Implements a Model Context Protocol server for integration with MCP-compatible agents and tooling.  
  - Accessible at `https://agent.thoughtspot.app/mcp`.

- **ThoughtSpot data analytics integration**  
  - Connects to ThoughtSpot to run search and analytics operations on your data.  
  - Designed to let agents perform data exploration and analysis workflows programmatically.

- **OAuth 2.1 authentication**  
  - Uses OAuth 2.1 for secure authorization to ThoughtSpot resources.  
  - Supports agent-based access with proper user or service credentials.

- **Containerization and deployment assets**  
  - `Dockerfile` provided for building and running the MCP server in containers.  
  - `deploy/` directory with deployment-related configurations and/or scripts.  
  - `.dockerignore` for optimized Docker builds.

- **Automation & CI configuration**  
  - `.github/workflows/` directory for GitHub Actions or similar CI pipelines (e.g., build, test, publish).

- **Static assets & public interface**  
  - `public/` and `static/` directories for serving static resources (e.g., UI assets or docs for the MCP server endpoint, if required by the implementation).

- **Source-organized implementation**  
  - `src/` directory containing the main server logic, protocol handling, and integrations with ThoughtSpot.  
  - `scripts/` directory for helper scripts (e.g., local dev, build, or deployment automation).  
  - `test/` directory for automated tests.

- **Publishing documentation**  
  - `PUBLISHING.md` with instructions or guidelines related to releasing or publishing the MCP server (e.g., to registries or directories).

- **Open-source licensing**  
  - Distributed under the license documented in `LICENSE` (details available in the repository).

## Pricing

- No pricing information is provided in the available content. The GitHub repository appears to host the open-source implementation of the MCP server; usage of ThoughtSpot itself may be subject to separate licensing or subscription terms not detailed here.