# zabbix-mcp-server

**Category:** Monitoring  
**Brand:** zabbix  
**Source:** [GitHub – mpeirone/zabbix-mcp-server](https://github.com/mpeirone/zabbix-mcp-server)

## Overview

`zabbix-mcp-server` is an open‑source MCP (Model Context Protocol) server that integrates with Zabbix. It exposes Zabbix monitoring data and operations—such as hosts, items, triggers, templates, and problems—to AI assistants and other MCP‑compatible clients, with a strong focus on comprehensive API coverage and read‑only safety options.

## Features

- **MCP Server for Zabbix**  
  - Implements the Model Context Protocol for use with LLMs and MCP‑aware tools.  
  - Designed to act as a bridge between Zabbix and AI assistants.

- **Wide Zabbix API Coverage**  
  - 40+ tools/endpoints exposed through MCP (as stated in repo tagline).  
  - Access to:  
    - Hosts  
    - Items  
    - Triggers  
    - Templates  
    - Problems  
    - Other related monitoring entities (via Zabbix API).  

- **Read‑only Mode**  
  - Optional read‑only configuration to prevent write or modification operations from an AI assistant.  
  - Suitable for safe observability/inspection use cases.

- **Zabbix Monitoring Data Exposure**  
  - Surfaces monitoring information in a form that LLMs can query via MCP.  
  - Intended to let AI assistants inspect infrastructure state, incidents, and configuration via Zabbix.

- **Container & Deployment Assets**  
  - `Dockerfile` included for containerized deployment.  
  - `docker-compose.yml` provided for quick spin‑up of the MCP server with its dependencies.  

- **Configuration & Setup Documentation**  
  - `MCP_SETUP.md` for MCP‑specific integration steps.  
  - `config/` directory for server and Zabbix connection configuration.  

- **Scripts & Tooling**  
  - `scripts/` directory for helper scripts (e.g., running, building, or managing the server; details in repo).  

- **Python Project**  
  - Managed via `pyproject.toml` (Python packaging and dependencies).  

- **Open Source License**  
  - Licensed under **GPL-3.0**.

## Pricing

- No pricing information is provided. The project is open source and released under the GPL-3.0 license; it can be used and self‑hosted without a commercial plan indicated in the available content.

## Images

- Zabbix web interface overview: `https://www.zabbix.com/documentation/current/_images/web_interface_overview.png`  
- zabbix-mcp-server diagram/screenshot: `https://github.com/mpeirone/zabbix-mcp-server/raw/HEAD/images/zabbix-mcp-server.png`

## Metadata

- **Slug:** `zabbix-mcp-server`  
- **Tags:** `monitoring`, `cloud-native`, `observability`  
- **Brand logo:** `https://assets.zabbix.com/img/logo/zabbix_logo_500x131.png`