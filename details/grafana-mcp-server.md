# Grafana MCP Server

**Category:** MCP Server Directories & Lists  
**Brand:** Grafana  
**Source:** https://github.com/grafana/mcp-grafana

## Description
Grafana MCP Server is an open-source Model Context Protocol (MCP) server for Grafana, distributed as the `mcp/grafana` Docker image. It allows MCP-compatible tools and agents to query Grafana dashboards, metrics, and other Grafana APIs.

## Features
- **MCP-compatible server for Grafana**  
  Implements a Model Context Protocol server focused on interacting with Grafana.

- **Docker-based distribution**  
  Available as the `mcp/grafana` Docker image for containerized deployment.

- **Dashboard querying**  
  Exposes access to Grafana dashboards through MCP so tools can retrieve dashboard-related data.

- **Metrics access**  
  Enables querying of metrics exposed via Grafana APIs through the MCP server.

- **Grafana API integration**  
  Provides MCP tools with programmatic access to Grafana APIs (beyond just dashboards and metrics), depending on how you configure and use the server.

- **Open-source implementation**  
  Source code available on GitHub, with directory structure including examples, tests, and tooling configuration.

## Deployment & Integration
- Distributed as a Docker image: `mcp/grafana`.
- Designed to be used by MCP-compatible tools (such as AI assistants or other automation/agent frameworks that support MCP) to interact with a Grafana instance.

## Licensing
- Licensed under the **Apache-2.0** license.

## Pricing
- **Free & Open Source**  
  The project is open source under Apache-2.0 and can be used at no cost. Operational costs (e.g., hosting, Grafana instance, infrastructure) are separate and depend on your environment.