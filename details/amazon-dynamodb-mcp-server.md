# Amazon DynamoDB MCP Server

## Overview
The Amazon DynamoDB MCP Server is an official developer-focused MCP server for Amazon DynamoDB. It enables MCP-aware tools and agents to:
- Get expert DynamoDB data modeling guidance
- Validate DynamoDB data models end-to-end
- Analyze existing relational databases for migration to DynamoDB
- Execute DynamoDB API operations programmatically (locally or in AWS)

Category: `database-messaging-mcp-servers`  
Brand: Amazon Web Services (AWS)

## Features

### 1. Data Modeling Guidance
- **`dynamodb_data_modeling` tool**
  - Provides a complete DynamoDB Data Modeling Expert prompt.
  - Includes enterprise-level design patterns.
  - Covers cost optimization strategies.
  - Emphasizes multi-table design philosophy.
  - Guides through:
    - Requirements gathering
    - Access pattern analysis
    - Schema design for DynamoDB
  - Example usage: design a data model for an application (e.g., e‑commerce) using the MCP server.

### 2. Data Model Validation
- **`dynamodb_data_model_validation` tool**
  - Loads a `dynamodb_data_model.json` definition.
  - Sets up DynamoDB Local for testing.
  - Creates tables defined in the model.
  - Populates tables with test data.
  - Executes all defined access patterns against the test environment.
  - Produces and saves detailed validation results to `dynamodb_model_validation.json`.

### 3. Source Database Analysis (MySQL/Aurora)
- **`source_db_analyzer` tool**
  - Analyzes existing MySQL or Amazon Aurora databases.
  - Extracts:
    - Database schema structure
    - Access patterns from Performance Schema
  - Generates timestamped analysis files for use with `dynamodb_data_modeling` to assist in designing a DynamoDB data model.
  - Requires:
    - AWS RDS Data API
    - Credentials stored in AWS Secrets Manager

### 4. DynamoDB Command Execution
- **`execute_dynamodb_command` tool**
  - Executes AWS CLI DynamoDB commands.
  - Can target:
    - DynamoDB Local
    - AWS DynamoDB in the cloud
  - Supports all DynamoDB API operations.
  - Automatically configures credentials for local testing environments.
  - Example usage: create tables in a specified AWS account and region (e.g., `us-east-1`) based on a generated data model.

### 5. MCP Integration
- Designed as an MCP server consumable by MCP-aware clients (e.g., Kiro, Cursor, VS Code via MCP integrations).
- Exposes the four tools (`dynamodb_data_modeling`, `dynamodb_data_model_validation`, `source_db_analyzer`, `execute_dynamodb_command`) to those clients.

## Prerequisites
- `uv` installed (from Astral or the `uv` GitHub repository).
- Python 3.10 installed via `uv` (e.g., `uv python install 3.10`).
- AWS credentials configured with access to required AWS services.

## Installation & Configuration

### General / Kiro Example
- Add the server to the MCP configuration file (e.g., for Kiro: `.kiro/settings/mcp.json`).
- Typical configuration fields include:
  - `command`: e.g., `uvx`
  - `args`: e.g., `["awslabs.dynamodb-mcp-server@latest"]`
  - `env` (example):
    - `FASTMCP_LOG_LEVEL`: `ERROR`
  - `disabled`: `false`
  - `autoApprove`: `[]`
- Default configuration sets `AWS_REGION` to `us-west-2`; this can be changed in the MCP configuration after installation.

### Windows Installation
- Uses a slightly different MCP server configuration:
  - `type`: `stdio`
  - `command`: `uv`
  - `args` (conceptually):
    - `tool`
    - `run`
    - `--from`
    - `awslabs.dynamodb-mcp-server@latest`
    - `awslabs.dynamodb-mcp-server.exe`
  - Includes fields such as:
    - `disabled`: `false`
    - `timeout`: e.g., `60`

## Pricing
- No pricing information is provided in the available content.
