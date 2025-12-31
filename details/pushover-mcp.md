# Pushover MCP

**Category:** Messaging MCP Servers  
**Slug:** pushover-mcp  
**Source:** https://github.com/ashiknesin/pushover-mcp

## Description
Pushover MCP is a Model Context Protocol (MCP) server that lets MCP-compatible AI agents and workflows send instant notifications through the Pushover.net service. It acts as a bridge between AI tools and Pushover, enabling programmatic push alerts to registered devices.

## Features
- **Model Context Protocol implementation**
  - Fully implements the MCP specification for interoperability with MCP-based systems.
- **Pushover.net integration**
  - Sends notifications to devices via the Pushover.net API.
  - Requires Pushover application token and user key obtained from the Pushover dashboard.
- **Single unified tool interface**
  - Exposes one MCP tool, `send`, for sending notifications.
- **`send` tool capabilities**
  - Sends a notification via Pushover to the configured user.
  - Designed for use inside MCP-compatible AI agents and workflows.
- **CLI-based MCP server**
  - Can be run via `npx pushover-mcp@latest start` with token and user parameters.
- **IDE integration (Cursor)**
  - Can be added to Cursor IDE as an MCP server using a custom command.
  - Supports global installation via `npx`.
  - Supports project-specific configuration via `.cursor/mcp.json`.

## Configuration
- Requires credentials from Pushover.net dashboard:
  - Application/API token
  - User key (user identifier)
- Credentials are passed to the MCP server via CLI flags (e.g., `--token`, `--user`) when starting the server.

## Usage
- **As an MCP server**
  - Start the server with `npx -y pushover-mcp@latest start --token YOUR_TOKEN --user YOUR_USER`.
  - Register it as an MCP server in compatible environments (e.g., Cursor, other MCP clients).
- **Within Cursor IDE**
  - Add a new MCP server in `Cursor Settings → MCP`.
  - Set the command to the `npx` invocation with your Pushover credentials.
  - Alternatively configure the server in a `.cursor/mcp.json` file for project-level usage.

## Pricing
- No pricing information is provided for this MCP implementation in the available content. (Note: Pushover.net itself may have its own pricing, but it is not specified here.)

## License
- The repository includes a `LICENSE` file; specific license terms are not detailed in the provided content and should be checked directly in the repository.