---
title: Stytch MCP Server
description: Authentication and identity MCP server that exposes Stytch OAuth 2.1 capabilities for AI agents and developer tools.
slug: stytch-mcp-server
brand: Stytch
brand_logo: https://stytch.com/logo.png
category: security-attestation-mcp-servers
tags:
  - authentication
  - identity-management
  - security
source_url: https://stytch.com/docs/guides/connected-apps/mcp-server-overview
images:
  - https://images.ctfassets.net/oggad6svuzkv/2izk84CwlnVlXSndIo2IOX/3b3a90cd5c45e26dfec353f64fdf75f4/stytch-open-graph.png
  - https://images.ctfassets.net/oggad6svuzkv/4Yz7KUaX0oA0aSOrG4aS9g/8f207258a9fdb7bd4ae6f84a699cf7ee/stytch-logo-dark.svg
---

## Overview

Stytch MCP Server is a remote Model Context Protocol (MCP) server at `http://mcp.stytch.dev/mcp` that exposes Stytch authentication and identity capabilities via OAuth 2.1 for AI agents and developer tools. It uses Stytch as the underlying identity provider and integrates with MCP clients through standardized OAuth-based authorization flows.

## Features

- **MCP-based auth integration**  
  - Implements the Model Context Protocol so AI agents and tools can discover and use authentication functionality remotely.  
  - Treats MCP clients as OAuth Connected Apps in Stytch.

- **OAuth 2.1 authorization code flow**  
  - MCP clients request access to a user’s account using the `authorization_code` grant type.  
  - Supports a complete MCP authorization flow using Stytch as the auth provider.

- **Access token validation**  
  - Validates Stytch-issued access token JWTs on MCP client initialization.  
  - Detects missing, invalid, or expired tokens.  
  - On failure, responds with HTTP `401 Unauthorized` and a `WWW-Authenticate` header in the format defined by RFC 9728.  
  - Directs clients to a Protected Resource Metadata (PRM) document via the `resource_metadata` attribute.

- **Protected Resource Metadata (PRM) support**  
  - Serves a `.well-known/oauth-protected-resource` document that MCP clients can discover from the `WWW-Authenticate` header.  
  - Enables standards-based discovery of how to obtain and use access tokens for the server.

- **Stytch React Component for consent**  
  - Uses the Stytch-hosted React component to handle the OAuth consent step in the browser.  
  - Can be embedded either in an existing frontend application or directly in a standalone MCP server UI.

- **Reference implementation / example server**  
  - Publicly accessible reference at `https://mcp.stytch.dev/` demonstrating:  
    - Initial connection without credentials and resulting 401 response.  
    - Example `WWW-Authenticate` header containing `resource_metadata="https://mcp.stytch.dev/.well-known/oauth-protected-resource"`.

- **SDK-based token introspection (Node example)**  
  - Node.js implementations can use the official `stytch` backend SDK.  
  - Supports validating access tokens through Stytch’s **Introspect Access Token** API for robust token checking.

## Use Cases

- Securely exposing application actions (e.g., identity-aware operations) to AI agents over MCP.
- Adding OAuth-based, Stytch-backed authentication to custom MCP servers.  
- Demonstrating or prototyping MCP authorization flows using a standards-based OAuth provider.

## Pricing

- Not specified in the provided content for the Stytch MCP Server itself. Refer to the main Stytch documentation and pricing pages for details on Stytch product and usage pricing.