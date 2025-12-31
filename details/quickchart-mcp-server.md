# QuickChart MCP Server

## Overview
QuickChart MCP Server is a Model Context Protocol (MCP) server that integrates with the QuickChart.io API to generate chart images programmatically. It enables agents or tooling-compatible clients to create various types of charts via MCP tools.

- **Category:** Data Visualization
- **Technology:** MCP server (Node/TypeScript project)
- **License:** MIT
- **Source:** https://github.com/GongRzhe/Quickchart-MCP-Server

## Features
- **MCP Integration**
  - Implements a Model Context Protocol server for chart generation.
  - Exposes chart-generation capabilities as MCP tools for agents.

- **Chart Generation via QuickChart.io**
  - Uses the QuickChart.io API to generate chart images.
  - Supports programmatic creation of chart images from structured chart configuration.
  - Designed to work with “various types of charts” supported by QuickChart (e.g., bar, line, pie, etc. via QuickChart configuration schemas).

- **Tooling & Automation**
  - Allows automated chart creation in workflows that support MCP servers.
  - Suitable for use by AI agents or other MCP-compatible clients to request charts dynamically.

- **Project & Deployment**
  - Source structure includes TypeScript configuration (`tsconfig.json`).
  - Includes `Dockerfile` for containerized deployment.
  - Distributed as an npm package (with `.npmignore` and `package.json`).

## Use Cases
- Generating data visualizations on demand from within MCP-enabled AI agents or tools.
- Integrating chart image generation into automated reporting or analysis pipelines using QuickChart.io.

## Pricing
No pricing information is provided in the available content. The project is open source under the MIT license; usage of QuickChart.io itself may be subject to QuickChart’s own pricing or usage limits (not specified in this repository content).