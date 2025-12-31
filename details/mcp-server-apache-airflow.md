# mcp-server-apache-airflow

**Category:** Workflow Automation MCP Servers  
**Tags:** apache-airflow, workflow, orchestration  
**License:** MIT  
**Source:** https://github.com/yangkyeongmo/mcp-server-apache-airflow  
**PyPI:** https://pypi.org/project/mcp-server-apache-airflow/

## Description
An MCP server that connects to Apache Airflow using the official Airflow Python client, allowing LLM agents and Model Context Protocol-compatible tools to inspect and interact with Airflow DAGs and workflows.

## Features
- **Model Context Protocol (MCP) server** for Apache Airflow
- **Integration via official Airflow client** to communicate with an existing Airflow instance
- **DAG inspection capabilities** (intended for exploring DAGs and workflows programmatically)
- **Workflow interaction support** for LLM agents (e.g., triggering or managing workflows via MCP, as supported by the underlying implementation)
- **Dockerfile included** for containerized deployment
- **Python package distribution** available on PyPI (`mcp-server-apache-airflow`)
- **Test suite** present under `test/` directory
- **Makefile** for common development or build tasks
- **Config and tooling files** (e.g., `.tool-versions`, `.gitignore`) for reproducible development environment

> Note: The GitHub listing shown is partial; more specific operations (e.g., which DAG actions are exposed as MCP tools) would be defined in the source under `src/`.

## Pricing
- Open-source, MIT-licensed.  
- No paid plans are indicated in the available content.