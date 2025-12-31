# Storyblok MCP Server

**Category:** Content Management MCP Servers  
**Website:** https://mcp.pipedream.com/app/storyblok

## Overview
Storyblok MCP Server connects Storyblok’s headless, API-based CMS to the Model Context Protocol (MCP), allowing agents and MCP-compatible clients to programmatically manage and query content stored in Storyblok.

## Features
- **MCP integration**: Exposes Storyblok CMS capabilities via the Model Context Protocol so MCP-enabled agents and apps can use Storyblok content.
- **Headless, API-based CMS**: Works with Storyblok’s headless CMS architecture, enabling structured content delivery via APIs.
- **Programmatic content operations**: Designed for managing and querying Storyblok content from agents and chat-based tools (e.g., list, fetch, or update content models and entries, subject to Storyblok permissions and API behavior).
- **Static MCP server endpoint**: Single, static MCP server URL usable across clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic setup**: The same MCP server URL is intended to work with any compatible MCP client; configuration is done on the client side.
- **Authentication at connection time**: Authentication is performed when adding the MCP server to your application, rather than using client-specific URLs.
- **Configuration documentation**: A dedicated configuration page explains how to add and configure the server for different chat clients (via the linked Configuration page).

## Usage
- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to an MCP-compatible client or application.
- Authenticate when prompted by the client during setup.

## Pricing
The provided content does not list any pricing or plans for the Storyblok MCP Server.