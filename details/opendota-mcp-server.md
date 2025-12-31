---
title: OpenDota MCP Server
slug: opendota-mcp-server
brand: opendota
brand_logo: https://www.opendota.com/assets/images/logo.png
source_url: https://github.com/asusevski/opendota-mcp-server
category: data-analysis-exploration-mcp-servers
tags:
  - gaming
  - analytics
  - api
  - mcp
  - dota-2
featured: false
---

## Overview

OpenDota MCP Server is a Model Context Protocol (MCP) server implementation that connects to the OpenDota API. It allows LLMs and AI assistants to access Dota 2 data—such as real-time statistics, match data, and player information—through a standardized MCP interface.

## Features

- MCP server implementation for OpenDota
- Access to OpenDota API data via a standard MCP interface
- Retrieval of real-time Dota 2 statistics
- Access to match data and related analytics
- Access to player information and statistics
- Designed for integration with LLMs and AI assistants
- Can be installed and run locally (e.g., via Python environment)
- Supports integration with Claude Desktop via MCP
- Example client included for testing and experimentation
- Configuration via environment variables (with `.env.example` provided)
- Dockerfile for containerized deployment
- Test suite included in `tests` directory

## Installation

- Install via Smithery for Claude Desktop using the published server on Smithery.
- Manual installation by cloning the repository and setting up a Python environment (details in the project README).

## Usage

- Configure environment using the provided `.env.example` as a template.
- Run the server directly with Python.
- Integrate with Claude Desktop by adding the server to `claude_desktop_config.json` following the MCP quickstart guide.
- Optionally use the included example client to interact with the server tools.

## Security

- Project includes a referenced third-party security assessment badge (details in the repository README).

## Pricing

- Not specified in the available content; the project is hosted on GitHub and includes a LICENSE file, indicating it is open-source, but no explicit pricing plans are listed.