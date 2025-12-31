---
title: Webflow MCP Server
slug: webflow-mcp-server
brand: Webflow
brand_logo: https://assets-global.website-files.com/6134b75e7f24347e0c5f7bdc/6134b75e7f2434fa625f7c01_webclip.png
category: content-management-mcp-servers
tags:
  - cms
  - website
  - content-management
images:
  - https://assets-global.website-files.com/5d3e104d994f1151b200d0f3/5f4e9fd1954f6b3117c0e3b9_webflow-og-image.png
  - https://assets-global.website-files.com/6134b75e7f24347e0c5f7bdc/6134b75e7f2434fa625f7c01_webclip.png
source_url: https://developers.webflow.com/mcp/reference/overview
---

## Overview

Webflow MCP Server is a Model Context Protocol (MCP) server that connects AI agents directly to Webflow projects via Webflow’s Data and Designer APIs. It enables AI-powered tools (such as Claude Desktop, Cursor, and Windsurf) to interact with Webflow sites and CMS content over SSE at `https://mcp.webflow.com/sse`, using OAuth-based authentication.

## Features

### Core Capabilities
- **AI-driven Webflow control**: Exposes Webflow APIs as MCP tools so AI agents can work with sites and CMS content using natural language instructions.
- **OAuth 2.1 authentication**: Connects AI environments to Webflow projects using OAuth-based authorization (as described in the reference docs).
- **Data API access**: Enables reading and managing site data, including CMS collections and other structured content (via Data API tools).
- **Designer API access**: Allows agents to modify the visual canvas, elements, and styles within Webflow projects (via Designer API tools).

### Build & Design
- **Create layouts**:
  - Build responsive sections, containers, and grids.
  - Configure appropriate breakpoints for responsive design.
- **Style elements**:
  - Apply and manage classes.
  - Modify CSS properties.
  - Manage design variables.
- **Build components**:
  - Create reusable component definitions for use across pages.
- **Design systems**:
  - Set up color schemes.
  - Define typography scales.
  - Configure spacing systems.

### Content & Site Data Management
- **Manage collections and CMS content**:
  - Manage Webflow CMS collections and their items through Data API tools.
- **Manage assets and other site data**:
  - Work with assets and other project data exposed via Webflow APIs.
- **Work with custom code**:
  - Access and manage custom code areas exposed by the APIs.

### Workflow & Automation
- **Automate workflows**:
  - Use AI agents to perform repetitive content and design operations inside Webflow.
- **Natural-language operations**:
  - Describe desired changes in natural language; the agent uses MCP tools to call Webflow’s APIs, removing the need to handcraft API requests.

### Beta Improvements (Optional Early Access)
- **Consolidated tools**:
  - Fewer, more powerful MCP tools to cover broader operations.
- **Batch operations**:
  - Update multiple items, pages, or elements in a single call.
- **Performance enhancements**:
  - Faster response times.
  - Optimized data transfer.
  - Reduced latency for API operations.

## Integration & Usage

- **Supported AI environments**:
  - Designed for AI-powered tools such as Claude Desktop, Cursor, and Windsurf.
- **Connection endpoint**:
  - MCP server available at `https://mcp.webflow.com/sse`.
- **Installation & setup**:
  - Install and configure the MCP server within supported AI tools.
  - Authenticate with OAuth to link to specific Webflow projects.
- **Reference resources** (from Webflow docs):
  - Getting started guide for installation and OAuth setup.
  - Prompt library with examples for tasks like image optimization, SEO audits, and style refactoring.
  - Detailed list of available Data API and Designer API tools.
  - Architectural and authentication overview.

## Pricing

The provided content does not specify any pricing or plans for the Webflow MCP Server.