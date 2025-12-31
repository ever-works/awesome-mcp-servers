# AWS Cost Explorer MCP Server

## Overview
AWS Cost Explorer MCP Server is an MCP (Model Context Protocol) server that exposes AWS spend and usage data so AI agents and MCP-compatible clients (such as Claude Desktop) can query and analyze AWS costs. It integrates with AWS Cost Explorer for billing data and Amazon Bedrock model invocation logs in CloudWatch for generative AI usage insights.

- **Category:** Finance & Market Data MCP Servers  
- **Vendor / Brand:** Amazon Web Services  
- **Source:** [GitHub – aarora79/aws-cost-explorer-mcp-server](https://github.com/aarora79/aws-cost-explorer-mcp-server)

## Features

### Cost and Usage Data Access
- Retrieves AWS spend data via **AWS Cost Explorer**.  
- Retrieves **Amazon Bedrock** usage data via **Model Invocation Logs** stored in **Amazon CloudWatch**.  
- Makes cost and usage information accessible via Anthropic’s **Model Context Protocol (MCP)** for programmatic and agent-based analysis.

### MCP Integration
- Implements an **MCP server** that can be consumed by MCP-compatible clients (e.g., Claude Desktop).  
- Exposes tools/endpoints defined by MCP so AI agents can query AWS billing and Bedrock usage as part of a conversation or workflow.

### Deployment Options
- **Local MCP server**: run on a local machine and connect directly from Claude Desktop.  
- **Remote MCP server**: can be deployed on **Amazon EC2** to serve multiple users or agents.  
- Supports running as a **“secure” remote MCP server over HTTPS** (as described in the secure remote MCP server section of the project).

### Implementation & Tooling
- Implemented in Python (core logic in files such as `server.py` and `app.py`).  
- Includes **Dockerfile** for containerized deployment.  
- Uses **pyproject.toml** for dependency and project configuration.  
- Includes sample/auxiliary clients such as:
  - `mcp_sse_client.py` – an SSE-based MCP client implementation.
  - `langgraph_agent_mcp_sse_client.py` – example integration with a LangGraph-based agent using MCP over SSE.
- Repository includes assets (e.g., `img/`) and configuration files (`.gitignore`, `uv.lock`).

### Licensing
- Distributed with an open-source **LICENSE** file in the repository (see GitHub project for exact license terms).

## Pricing
- This is an **open-source** project hosted on GitHub.  
- No explicit pricing or paid plans are described in the available content; usage costs are limited to your underlying **AWS charges** (e.g., Cost Explorer, CloudWatch, Bedrock) and any infrastructure used to host the MCP server (e.g., EC2).