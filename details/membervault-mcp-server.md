# Membervault MCP Server

## Overview
The Membervault MCP Server connects MemberVault, a content and engagement platform built around the Content Ladder Framework for creators, to MCP-compatible chat clients via Pipedream Connect.

- **Type:** MCP server / integration
- **Platform:** MemberVault via Pipedream Connect
- **Category:** Content management MCP servers
- **Use cases:** Managing and automating content and engagement workflows for creators using the MemberVault platform.

## Features
- **MCP Server Endpoint**  
  - Static MCP server URL for all clients:  
    `https://mcp.pipedream.net/v2`
  - Works as a shared endpoint; authentication is performed per client when adding the server.

- **Chat Client Integration**  
  - Can be added to compatible chat-based applications as an MCP server.  
  - Supports configuration through a standardized MCP setup flow.  
  - Client-specific setup guidance available via the configuration documentation (linked from the app page).

- **Pipedream Connect Integration**  
  - Operates on top of Pipedream Connect infrastructure.  
  - Inherits Pipedream’s connection, authentication, and configuration model for MCP servers.

- **MemberVault Platform Context**  
  - Designed for creators using MemberVault’s Content Ladder Framework.  
  - Oriented around content management and engagement automation use cases.

*(The source content does not list additional tool methods, APIs, or specific MCP capabilities beyond the generic server URL and integration context.)*

## Authentication
- Authentication is performed when adding the server to an MCP-compatible application.  
- The same static URL is used for all clients; credentials / tokens are associated with each client’s configuration.

## Configuration
- Add the MCP server to a chat client using:
  - **Server URL:** `https://mcp.pipedream.net/v2`
- Further configuration details (such as environment variables, credentials, or scopes) are provided in the linked configuration documentation on Pipedream.

## Pricing
- The provided content does not include any pricing or plan information for the Membervault MCP Server or underlying MemberVault/Pipedream services.