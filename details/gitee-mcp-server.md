# Gitee MCP Server

**Category:** Repository & Code Analysis MCP Servers  
**Slug:** gitee-mcp-server  
**Brand:** Gitee  
**Source:** https://github.com/oschina/mcp-gitee  
**License:** MIT

![Gitee Logo](https://gitee.com/static/images/logo_en.svg)

## Overview

Gitee MCP Server is a Model Context Protocol (MCP) server implementation for the Gitee platform. It exposes tools that allow AI assistants and agents to interact with Gitee’s API to manage repositories, issues, and pull requests.

## Features

- **Model Context Protocol implementation** for the Gitee platform.
- **Gitee API integration** for programmatic access via AI agents.
- **Repository management capabilities**, such as interacting with repository data (via MCP tools).
- **Issue management** through tools that can create or manage issues on Gitee.
- **Pull request management** via MCP tools interacting with Gitee’s pull request APIs.
- **Tool-based interaction model**, designed for use by AI assistants rather than direct human UI.
- **Containerization support** via a provided Dockerfile for running the MCP server in Docker.
- **Build and automation scripts** (e.g., Makefile) to assist with building and running the server.
- **Documentation and examples** in the `docs/` directory and `README` files (including Chinese and English variants).
- **Utility modules** under `utils/` and additional supporting code under `operations/` and `npm/` directories to structure the MCP server’s functionality.

## Technical Details

- **Language / Runtime:** Go (based on presence of `go.mod` and `go.sum`).
- **Distribution / Packaging:** Source code repository with Dockerfile and npm-related assets, suitable for containerized or local deployment.
- **Repository Stats (at snapshot time):** 45 stars, 13 forks (GitHub).

## Pricing

- Not specified; the project is open source under the MIT License, and can be used according to that license’s terms.
