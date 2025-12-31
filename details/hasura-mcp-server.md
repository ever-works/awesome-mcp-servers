# Hasura MCP Server

An MCP server that lets MCP-compatible agents query and manipulate data via Hasura’s auto-generated GraphQL APIs.

- **Website / Source**: https://mcp.pipedream.com/app/hasura
- **Category**: Data Access & Integration MCP Servers
- **Tags**: GraphQL, API, data-integration
- **Provider**: Hasura (hosted via Pipedream Connect)

## Features

- **MCP-compatible data access**: Exposes a Model Context Protocol (MCP) server that agents and clients can use to interact with data through Hasura.
- **GraphQL API integration**: Utilizes Hasura’s auto-generated GraphQL APIs for querying and mutating data.
- **Static MCP server endpoint**: Single shared endpoint for all clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic configuration**: The same MCP server URL can be used across different chat or MCP-compatible clients.
- **Authentication at client setup**: Authentication is handled when adding the MCP server to your application or client configuration.
- **Configuration documentation**: A configuration page (linked from the app) provides setup guidance for integrating the server into supported clients.
- **Hosted by Pipedream Connect**: Infrastructure and delivery handled by Pipedream’s integration platform.

## Usage

- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add it to your MCP-compatible app or chat client and complete authentication as instructed in the client’s configuration.

## Pricing

- Not specified in the provided content.