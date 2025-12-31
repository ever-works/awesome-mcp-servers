# SmartrMail MCP Server

The SmartrMail MCP Server is an integration that exposes SmartrMail (an ecommerce-focused email marketing platform) through the Model Context Protocol (MCP), enabling agents and workflows to manage ecommerce email marketing tasks programmatically.

- **Website / Source**: https://mcp.pipedream.com/app/smartrmail
- **Category**: Business & Commerce – MCP Servers
- **Tags**: email-marketing, e-commerce, campaigns
- **MCP Server URL**: `https://mcp.pipedream.net/v2`

## Overview

This MCP server provides a standardized interface between SmartrMail and MCP-compatible clients (such as chat-based agents or workflows). Once added and authenticated in a client that supports MCP, it can be used to interact with SmartrMail’s ecommerce email marketing features programmatically.

## Features

- **MCP Integration**
  - Exposes SmartrMail via the Model Context Protocol.
  - Usable from any MCP-compatible client or agent.
  - Central static server URL (`https://mcp.pipedream.net/v2`) for all clients.

- **Programmatic Email Marketing Control**
  - Designed for managing ecommerce email marketing tasks via agents/workflows.
  - Suitable for automating operations typically done in a “smarter email app for ecommerce” (e.g., campaigns and related workflows), subject to what the MCP tools expose in the client.

- **Client-Agnostic Setup**
  - Single static endpoint for all clients; authentication happens when adding the server in each application.
  - Compatible with multiple chat or workflow clients that support MCP configuration.

- **Pipedream-Hosted**
  - Hosted and provided through Pipedream Connect’s MCP infrastructure.

## Configuration

- **MCP Server URL**: `https://mcp.pipedream.net/v2`
- **Setup**:
  - Add this URL as an MCP server in your MCP-compatible client.
  - Authenticate within the client when prompted.
  - Refer to the client’s documentation or the Pipedream **Configuration** page for detailed setup steps.

## Pricing

- Not specified in the provided content. No plan or pricing details are available from the current source.
