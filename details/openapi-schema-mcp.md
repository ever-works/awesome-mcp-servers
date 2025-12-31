# OpenAPI Schema MCP

A Model Context Protocol (MCP) server that exposes OpenAPI schema information to LLMs, enabling schema-aware navigation and querying without bloating context.

- **Website/Source:** https://github.com/hannesj/mcp-openapi-schema
- **Category:** Development Tools – MCP Servers
- **Tags:** openapi, api, exploration

## Description
OpenAPI Schema MCP is an MCP server for Large Language Models (such as Claude) that loads OpenAPI specifications and exposes them via structured tools. This allows LLMs to explore API endpoints, parameters, request/response schemas, components, and security schemes programmatically rather than via raw schema text.

## Features
- **MCP Server for OpenAPI Schemas**
  - Implements a Model Context Protocol server dedicated to OpenAPI specifications.
  - Designed to let LLMs explore large schemas efficiently without including the entire spec in context.

- **Schema-Aware Exploration Tools**
  - `list-endpoints` – enumerate available API endpoints.
  - `get-endpoint` – retrieve details for a specific endpoint (path + method).
  - `get-request-body` – fetch the request body schema for an operation.
  - `get-response-schema` – get the response schema for an operation.
  - `get-path-parameters` – list path parameters for an endpoint.
  - `list-components` – list defined components/schemas in the spec.
  - `get-component` – retrieve a specific component definition.
  - `list-security-schemes` – list configured security schemes.
  - `get-examples` – access examples defined in the OpenAPI spec.
  - `search-schema` – search within the schema for relevant definitions.

- **CLI Usage**
  - Can be run as a command-line MCP server using a specific OpenAPI schema file.

- **Claude Desktop Integration**
  - Configurable via `claude_desktop_config.json`.
  - Supports installation on macOS and Windows using the standard Claude Desktop config locations:
    - macOS: `~/Library/Application Support/Claude/claude_desktop_config.json`
    - Windows: `$env:AppData\Claude\claude_desktop_config.json`

- **Claude Code (CLI) Integration**
  - Can be registered as an MCP server within Claude Code.
  - Supports project vs global scope configuration via flags such as `-s` / `--scope` (`project`, `global`).
  - Once configured, can be invoked in Claude Code sessions by asking questions about the OpenAPI schema (e.g., available endpoints, request/response structure, parameters).

- **Example Use Cases**
  - Ask what endpoints exist in an API.
  - Inspect details for specific operations (e.g., `POST /pets`).
  - Discover required parameters for an endpoint (e.g., `GET /pets/{petId}`).
  - Retrieve request body definitions for creating or updating resources.
  - Understand response schemas for different operations.
  - Explore all schemas/components and inspect a particular definition.

## Pricing
No pricing information is provided in the available content. The project appears to be an open-source GitHub repository.