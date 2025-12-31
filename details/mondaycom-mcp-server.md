# monday.com MCP Server

monday.com (OAuth) MCP Server is an MCP endpoint for monday.com’s Work OS that uses OAuth to enable secure, AI-driven automation of boards, tasks, and project workflows.

- **Website / Source**: https://mcp.pipedream.com/app/monday_oauth
- **Category**: Project Management MCP Servers
- **Brand**: monday.com / Pipedream
- **MCP Server URL**: `https://mcp.pipedream.net/v2`

## Features

- **OAuth-based authentication**
  - Uses monday.com OAuth for secure authorization.
  - Authentication occurs when adding the server to your client; the URL itself is static.

- **Static MCP endpoint**
  - Single, static MCP URL (`https://mcp.pipedream.net/v2`) used across all compatible clients.
  - Simplifies configuration and reuse across different AI/chat applications.

- **Integration with monday.com Work OS**
  - Connects AI clients to monday.com’s project and work management platform.
  - Enables AI-driven access to monday.com resources such as boards, tasks, and workflows (via Pipedream’s MCP capabilities).

- **Workflow and task automation**
  - Designed to support automation around boards, tasks, and project workflows within monday.com.
  - Suitable for building AI assistants that can interact with project data and process workflows.

- **Client-agnostic setup**
  - Documented as working with “every client” that supports MCP.
  - Can be added to multiple chat or AI clients via the same configuration URL.

## Configuration / Usage

- Add the MCP server URL `https://mcp.pipedream.net/v2` to your MCP-compatible chat or AI client.
- Authenticate with monday.com via OAuth during client setup.
- Refer to the Pipedream MCP **Configuration** page for detailed client-specific setup steps.

## Pricing

- The provided content does not specify any pricing or plans for the monday.com MCP Server or related Pipedream usage.