# Interzoid MCP Server

**Category:** Data Analysis & Exploration – MCP Servers  
**Brand:** Interzoid  
**Source:** https://mcp.pipedream.com/app/interzoid

## Overview
Interzoid MCP Server is an MCP (Model Context Protocol) server integration that enables AI/ML-based cloud data engineering workloads over cloud database tables and CSV (and similar tabular) files. All data workloads run in the cloud, accessible via a static MCP server URL.

- **MCP Server URL:** `https://mcp.pipedream.net/v2`
- Works with multiple chat / MCP-compatible clients
- Supports connecting to cloud data sources such as database tables and CSV/TSV/Excel files

## Features

### MCP Server & Connectivity
- Static MCP server URL (`https://mcp.pipedream.net/v2`) shared across clients
- Authentication handled when adding the server to a compatible application
- Designed to integrate with multiple chat / MCP clients for AI-assisted workflows
- Cloud-based execution of data engineering workloads (no local processing required)

### Data Sources
- Connect to cloud database tables
- Connect to CSV files
- Supports other tabular files for match reporting (CSV, TSV, Excel)

### Available Tools / Actions
Interzoid MCP Server exposes three primary tools as MCP actions:

1. **Get Organization Match Score**  
   - Computes a similarity / match score between two organization names.  
   - Output: Score from 0–100 indicating likelihood that the two organization names refer to the same entity.

2. **Get Full Name Match Score**  
   - Computes a similarity / match score between two individual (person) names.  
   - Output: Score from 0–100 indicating likelihood that the two names refer to the same individual.

3. **Generate Match Report**  
   - Generates a match report over a dataset table or file.  
   - Supported input formats: CSV, TSV, Excel.  
   - Intended for bulk / dataset-level matching and similarity analysis.

### Use Cases (Implied from Features)
- Entity resolution across organization names (e.g., deduplicating company records)
- Person-name matching and de-duplication across datasets
- Bulk similarity analysis and match reporting for tabular datasets
- AI/ML-driven data quality and data engineering workflows on cloud data

## Configuration
- Users connect their Interzoid account through the Pipedream interface.
- Once connected, the same MCP server URL can be used across supported clients.
- Additional setup details are available via the referenced configuration page on the source site.

## Pricing
- No pricing information is provided in the available content.