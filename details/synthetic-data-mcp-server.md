# Synthetic Data MCP Server

**Website:** https://awslabs.github.io/mcp/servers/syntheticdata-mcp-server  
**Category:** Testing & Debugging Tools  
**Tags:** synthetic-data, testing, ml

## Overview
Synthetic Data MCP Server is a Model Context Protocol (MCP) server for generating, validating, and managing realistic synthetic data. It supports business-driven synthetic data generation, safe data processing with pandas, data quality checks, and loading data into storage systems such as Amazon S3.

## Features

### Synthetic Data Generation
- **Business-driven generation**: Generate synthetic data instructions based on high-level business descriptions.
- **Structured generation instructions**: Convert business descriptions into structured data generation instructions (e.g., schemas, rules).

### Data Processing & Code Execution
- **Safe pandas code execution**: Run pandas code in a restricted environment.
  - Automatic detection of DataFrames.
  - Restricted execution context to reduce risk when running arbitrary code.

### Data Validation & Quality
- **JSON Lines validation**:
  - Validate JSON Lines (JSONL) data.
  - Convert JSON Lines data into CSV format.
- **Data validation**:
  - Validate overall data structure.
  - Check referential integrity across related tables.
  - Save validated data as CSV files.
- **Referential integrity checking**:
  - Verify relationships between tables (e.g., foreign key–like consistency).
- **Data quality assessment**:
  - Identify potential issues in data models.
  - Includes checks aligned with 3NF (Third Normal Form) validation concepts.

### Storage & Integration
- **Storage integration (S3)**:
  - Load generated and validated data to storage targets such as Amazon S3.
  - Support for multiple file formats:
    - CSV
    - JSON
    - Parquet
  - Partitioning options for organizing data in storage.
  - Storage class configuration.
  - Encryption settings for stored data.

## Prerequisites
- `uv` installed (via Astral / GitHub instructions).
- Python 3.10 installed via `uv` (`uv python install 3.10`).
- AWS account and credentials with appropriate permissions.
  - Configure with `aws configure` or environment variables.

## Installation

Configuration examples are provided for integrating the MCP server into editors such as Cursor and VS Code.

### Example (non-Windows)
- Use `uvx` to run `awslabs.syntheticdata-mcp-server`.
- Typical configuration parameters:
  - `command`: `uvx`
  - `args`: `["awslabs.syntheticdata-mcp-server"]`
  - `env` examples:
    - `FASTMCP_LOG_LEVEL=ERROR`
    - `AWS_PROFILE=your-aws-profile`
    - `AWS_REGION=us-east-1`
  - `autoApprove`: `[]`
  - `disabled`: `false`

### Windows Installation
- Uses `uv` with `tool run` syntax.
- Typical configuration parameters:
  - `type`: `stdio`
  - `timeout`: `60`
  - `command`: `uv`
  - `args`: `["tool", "run", "--from", "awslabs.syntheticdata-mcp-server@latest", "awslabs.syntheticdata-mcp-server.exe"]`
  - `env` examples:
    - `FASTMCP_LOG_LEVEL=ERROR`
    - `AWS_PROFILE=your-aws-profile`
    - `AWS_REGION=us-east-1`

### AWS Authentication
- Uses the AWS profile specified in the `AWS_PROFILE` environment variable.
- Requires that local credentials remain valid and refreshed on the host.

## Pricing
No pricing information is provided in the available content.