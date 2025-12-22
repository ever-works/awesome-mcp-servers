# AWS S3 MCP Server

A sample Model Context Protocol (MCP) server that lets LLMs retrieve data (currently PDFs) from AWS S3 buckets and load it into the model’s context.

- **Brand:** Amazon Web Services (AWS)
- **Category:** mcp-server-directories-lists
- **Source:** https://github.com/aws-samples/sample-mcp-server-s3

## Features

- **MCP Server for AWS S3**  
  - Implements a Model Context Protocol (MCP) server backed by AWS S3.  
  - Designed to retrieve data such as PDF documents from S3 buckets for LLM use.

- **Resources Interface**  
  - Exposes AWS S3 data as **Resources** (conceptually similar to HTTP GET endpoints).  
  - Resources are used to load information directly into the LLM’s context.  
  - Currently supports **PDF documents only**.  
  - Supports up to **1000 S3 objects**.

- **Integration with Claude Desktop**  
  - Can be configured as an MCP server for Claude Desktop.  
  - Configuration file locations:  
    - macOS: `~/Library/Application Support/Claude/claude_desktop_config.json`  
    - Windows: `%APPDATA%/Claude/claude_desktop_config.json`

- **AWS Credentials Configuration**  
  - Requires AWS credentials to access S3 (details provided in the repository’s configuration section).

- **Build & Publish Workflow**  
  - Supports building source and wheel distributions into a `dist/` directory.  
  - Publishing to PyPI (or similar) uses credentials provided via:  
    - `--token` or `UV_PUBLISH_TOKEN`  
    - `--username` or `UV_PUBLISH_USERNAME`  
    - `--password` or `UV_PUBLISH_PASSWORD`

- **Debugging Support**  
  - MCP server runs over stdin/stdout (stdio).  
  - Recommended debugging workflow via the **MCP Inspector** tool.

## Pricing

- **Pricing:** Not specified. The project is published as an open-source sample on GitHub; see the `LICENSE` file in the repository for licensing and usage terms.
