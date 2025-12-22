# Sentry CLI MCP Example

## Overview
A CLI-based Model Context Protocol (MCP) server configuration that wraps the Sentry CLI, enabling tools like Warp to interact with Sentry through the standardized MCP interface. It serves as a reference implementation for running Sentry as an MCP server and configuring authentication (e.g., via environment variables).

- **Type:** MCP server configuration (CLI-based)
- **Brand:** Sentry
- **Category:** mcp-server-directories-lists
- **Slug:** `sentry-cli-mcp-example`
- **Source:** [Documentation link](https://docs.warp.dev/knowledge-and-collaboration/mcp#sentry)

## Features
- **Sentry CLI wrapper:** Exposes Sentry’s CLI functionality as an MCP server so that compatible clients (such as Warp) can use Sentry through MCP tools.
- **CLI-based MCP server:** Runs as a command-line process managed by the MCP client (e.g., Warp starts and stops the server as needed).
- **Authentication via environment variables:** Demonstrates how to configure Sentry authentication (such as tokens) using environment variables in the MCP configuration.
- **Standardized MCP interface:** Uses the Model Context Protocol to provide tools/data sources in a consistent way across different MCP-compatible clients.
- **Warp integration:** Can be added to Warp via the **MCP Servers** settings, allowing Warp’s agents to call Sentry operations through MCP.
- **Configurable command and arguments:** Uses MCP’s CLI server properties (`command`, `args`) to define how the Sentry CLI is launched.
- **Environment configuration:** Supports an `env` object for passing required configuration (such as API tokens or Sentry-specific variables) to the CLI process.
- **Working directory control:** Can set `working_directory` to ensure relative paths used by the Sentry CLI resolve reliably across machines and sessions.
- **Reusable reference implementation:** Intended as a reference configuration that can be adapted to other projects or MCP clients needing Sentry integration.

## Configuration Notes
- Add as a **CLI Server (Command)** type MCP server in Warp’s MCP settings.
- Key configuration fields:
  - `command`: executable used to launch the Sentry MCP server (e.g., the Sentry CLI entrypoint).
  - `args`: array of command-line arguments passed to `command`.
  - `env`: key–value environment variables (e.g., Sentry auth tokens, organization/project config).
  - `working_directory`: directory from which the command is run; recommended to set explicitly when using relative paths.

## Pricing
No pricing information is provided in the referenced documentation. Refer to Sentry’s and Warp’s official sites for any related pricing details.
