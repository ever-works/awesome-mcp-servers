# Impression MCP Server

## Overview
Impression MCP Server is a Model Context Protocol (MCP) server that connects Impression’s secure eSignature capabilities to MCP-compatible chat or AI applications via a static server URL.

- **Category:** Business & Commerce – MCP Servers  
- **Provider / Brand:** Impression (via Pipedream)  
- **Primary Function:** Enable secure eSignature workflows and document signing operations through MCP.

## Features
- **Secure eSignature integration** – Exposes Impression’s eSignature and document-signing operations through an MCP server endpoint.
- **Static MCP server URL** – Uses a single, static endpoint for all clients:  
  `https://mcp.pipedream.net/v2`
- **Account-based authentication** – You connect your Impression account and authenticate when adding the server to your application.
- **Client-agnostic setup** – The same MCP URL works across different MCP-compatible chat clients and applications.
- **Configurable connection** – "Configure Impression" flow in the Pipedream UI to connect your account and select a client.
- **Tool-based actions (MCP tools)** – Provides a set of MCP tools/actions (listed as “Available tools”) that can be loaded and called by your MCP client for eSignature and workflow operations. (The specific actions are not enumerated on the page.)
- **Works with MCP configuration guides** – Can be integrated using client-specific instructions or the general MCP configuration documentation.

## Workflow / How It’s Used
1. Connect your Impression account in the Pipedream-based UI.  
2. Copy the static MCP server URL: `https://mcp.pipedream.net/v2`.  
3. Add this URL as an MCP server in your chosen chat/AI client.  
4. Authenticate when prompted in your application.  
5. Use the exposed MCP tools to perform eSignature and document-signing related operations.

## Pricing
The provided content does not include any pricing information or plan details for the Impression MCP Server.