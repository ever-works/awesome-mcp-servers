# Scalr MCP Server

**Category:** Cloud & DevOps – MCP Servers  
**Brand:** Scalr  
**Source:** https://mcp.pipedream.com/app/scalr

## Overview
Scalr MCP Server is an MCP (Model Context Protocol) server integration for Scalr, a remote state and operations backend for Terraform. It enables MCP-based access to Scalr so applications and chat clients can interact with Terraform state and operations through a unified MCP endpoint.

## Features
- **MCP-based access to Scalr**: Integrates Scalr as an MCP Server so compatible clients can use Scalr’s Terraform backend through the MCP protocol.
- **Remote state backend for Terraform**: Uses Scalr as a remote state store for Terraform configurations.
- **Operations backend for Terraform**: Provides access to Terraform operations (e.g., runs, apply workflows) via Scalr as the operations backend.
- **Full CLI support (via Scalr)**: Leverages Scalr’s full CLI support for managing Terraform infrastructure.
- **Quality-of-life enhancements (via Scalr)**: Integrates Scalr’s various usability and workflow features around Terraform state and operations.
- **Static MCP server URL**: Uses a single static MCP endpoint (`https://mcp.pipedream.net/v2`) that works for all supported clients.
- **Client-agnostic setup**: Same MCP server URL can be added to different chat or MCP-compatible applications; authentication is handled when adding the server.

## Setup & Usage
- **MCP Server URL**: `https://mcp.pipedream.net/v2`
- **Configuration**: Connect your Scalr account, select a client, and add the MCP server URL to your chosen chat/app client. Further configuration details are available on the Pipedream configuration page.

## Pricing
The provided content does not include any pricing or plan information for Scalr MCP Server.