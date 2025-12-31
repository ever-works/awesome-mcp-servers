# Plecto MCP Server

## Overview
Plecto MCP Server is an MCP (Model Context Protocol) server integration that connects MCP-compatible tools and chat clients to Plecto’s business performance dashboards. It enables programmatic access to real-time KPIs and performance data from Plecto via a single static server endpoint.

- **Category:** Data visualization
- **Use cases:** Access and surface real-time KPIs, metrics, and performance dashboards inside MCP-enabled applications or chat clients.

## Features
- **MCP server integration for Plecto** – Exposes Plecto’s performance and KPI data to any MCP-compatible client.
- **Static server URL for all clients** – Uses a single shared endpoint: `https://mcp.pipedream.net/v2`.
- **Per-client authentication** – Authentication is handled when adding the server to each application or chat client (credentials not embedded in the URL).
- **Chat client compatibility** – Designed to be added to various MCP-compatible chat clients to bring real-time Plecto data into conversational workflows.
- **Configuration guidance** – Supports setup via a general configuration flow, with a referenced “Configuration” page for detailed steps.

## Technical Details
- **MCP endpoint:** `https://mcp.pipedream.net/v2`
- **Provider platform:** Built and hosted via Pipedream Connect.

## Pricing
The provided content does not specify any pricing or plans for the Plecto MCP Server integration.