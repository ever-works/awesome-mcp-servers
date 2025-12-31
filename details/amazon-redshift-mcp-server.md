# Amazon Redshift MCP Server

**Category:** Database & Messaging MCP Servers  
**Brand:** Amazon Web Services

## Overview
The Amazon Redshift MCP Server is an open source Model Context Protocol (MCP) implementation that gives AI agents safe, structured access to Amazon Redshift data warehouses. It connects MCP-compatible tools (such as Amazon Q Developer CLI, Claude Desktop, and Kiro) to Redshift clusters so users can discover, explore, and analyze data and metadata using natural language.

## Features
- **MCP-based integration**
  - Implements the Model Context Protocol to connect AI agents with Amazon Redshift.
  - Acts as a bridge between conversational interfaces and Redshift clusters or workgroups.

- **Safe, structured access to Redshift resources**
  - Provides controlled access paths to Amazon Redshift resources rather than direct, unconstrained database access.
  - Uses AWS IAM permissions to govern what the MCP server can discover and query.

- **Metadata discovery and exploration**
  - Allows AI agents to dynamically discover database structures and schemas.
  - Supports exploration of tables and their relationships to give the agent context for query generation.

- **Query execution for analytics**
  - Translates natural language requests into appropriate Redshift Data API calls and SQL statements.
  - Supports execution and batch execution of SQL via `redshift-data:ExecuteStatement` and `redshift-data:BatchExecuteStatement`.
  - Retrieves query status and results with `DescribeStatement` and `GetStatementResult`.

- **Support for provisioned and serverless Redshift**
  - Uses `redshift:DescribeClusters` for provisioned clusters.
  - Uses `redshift-serverless:ListWorkgroups` and `GetWorkgroup` for Redshift Serverless environments.

- **Works with multiple MCP-compatible tools**
  - Integrates with:
    - Amazon Q Developer CLI
    - Claude Desktop
    - Kiro
    - Other MCP-compatible agents and workflows

- **Natural language interface to data**
  - Enables conversational querying of Redshift metadata and data.
  - Helps AI agents build context-aware execution plans based on cluster configuration and schemas.

- **Open source implementation**
  - Available in the AWS Labs GitHub repository.
  - Can be self-hosted and customized as part of existing data and analytics workflows.

- **Installation and environment setup (from provided content)**
  - Requires `uv` as a system dependency.
  - Relies on AWS IAM policies with permissions for Redshift, Redshift Serverless, and the Redshift Data API.

## Requirements
- **System**
  - `uv` installed on the machine running the MCP server (per blog prerequisites).

- **AWS**
  - An AWS account with Amazon Redshift (provisioned clusters and/or serverless workgroups).
  - IAM permissions including (as shown):
    - `redshift:DescribeClusters`
    - `redshift-serverless:ListWorkgroups`
    - `redshift-serverless:GetWorkgroup`
    - `redshift-data:ExecuteStatement`
    - `redshift-data:BatchExecuteStatement`
    - `redshift-data:DescribeStatement`
    - `redshift-data:GetStatementResult`

## Integrations
- Amazon Redshift (clusters and serverless workgroups)
- Amazon Q Developer CLI
- Claude Desktop
- Kiro
- Any MCP-compatible AI agent or workflow

## Pricing
No pricing information is provided in the source content. The component is described as an open source solution; any associated AWS service costs (for Amazon Redshift or related APIs) are not detailed in the provided text.