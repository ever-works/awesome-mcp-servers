# MCP Servers for Agents

**Brand:** Warp  
**Category:** MCP server directories & lists  
**Source:** https://docs.warp.dev/ambient-agents/mcp-servers-for-agents

## Description
“MCP Servers for Agents” is a Warp documentation guide that explains how Ambient Agents in Warp connect to and use Model Context Protocol (MCP) servers. It covers how to configure MCP servers (via JSON or YAML) so agents can securely call external tools, local services, and internal APIs from within the Warp environment.

## Features
- **MCP-based tool access for agents**  
  - Lets Ambient Agents call external tools and services via MCP servers.  
  - Supports integration with external APIs (e.g., GitHub, dbt) and custom/internal developer tools.

- **Multiple configuration delivery methods**  
  - **Inline JSON config** via the `--mcp` CLI flag, passing a full MCP JSON object as the configuration map for all MCP servers.  
  - **File-based config** by passing a file path whose contents follow the MCP JSON specification.

- **MCP JSON configuration standard support**  
  - Follows the published **MCP JSON configuration standard**.  
  - Accepts both JSON and YAML (YAML typically inside the broader agent config file).

- **MCP configuration schema and fields**  
  - Supports any number of MCP servers in a single configuration.  
  - Key fields:
    - `url`: Direct URL to an MCP server endpoint.  
    - `command` / `args`: Local executable and arguments for launching a local MCP server process.  
    - `env`: Environment variables passed to the MCP server command.
  - An `mcp_servers` field in the agent config overrides the default (empty) server set.

- **Integration with agent config files**  
  - MCP servers are typically defined inside a broader agent configuration, e.g. `warp-agent.json` or `warp-agent.yaml`.  
  - These config files can be:  
    - Passed directly as the agent’s config file when running.  
    - Referenced via `config_file` when creating tasks through Warp’s API.

- **Default behavior and permissions**  
  - If `mcp_servers` is omitted, the Ambient Agent runs **without** any MCP servers enabled.  
  - MCP permissions default to **allowing MCP tool calls**, with possible inheritance from user/profile settings.  
  - Notes that permission behavior is evolving as Warp phases out profiles for Ambient Agents.

- **Validation and requirements**  
  - Configuration must adhere to the MCP JSON specification.  
  - Inline or file-based config must be valid JSON (or valid YAML when used inside the agent config).

## Typical Use Cases
- Extending an Ambient Agent with access to:
  - External tools or APIs wrapped behind MCP interfaces.  
  - Local processes that expose MCP endpoints.  
  - Internal developer tools and internal APIs that should participate in ambient workflows.
- Centralizing MCP server definitions in shared `warp-agent.json` / `.yaml` configs for consistent agent behavior across teams.
