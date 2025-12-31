# 0codekit MCP Server

## Overview
The 0codekit MCP Server is an integration for 0CodeKit (formerly 1SaaS.co) that exposes low-code / no-code API and automation capabilities into the Model Context Protocol (MCP) ecosystem. It provides a static MCP server URL that can be connected from compatible chat clients (such as ChatGPT) to use 0codekit-powered automation tools.

## Key Details
- **Name:** 0codekit MCP Server  
- **Brand:** 0codekit  
- **Category:** Workflow automation MCP servers  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Use Cases:** Web & app development, low-code / no-code workflows, API-based automation

## Features
- **Static MCP Server Endpoint**  
  - Single, static URL (`https://mcp.pipedream.net/v2`) that works for every MCP-compatible client.  
  - Authentication handled when adding the server to your application.

- **Client Integration Guidance**  
  - Setup instructions and guides available for connecting from supported chat clients (e.g., ChatGPT / OpenAI).  
  - Central configuration resources via the MCP configuration page.

- **Available Tools (Actions)**  
  Currently exposes two actions as MCP tools:
  1. **Read Barcode**  
     - Reads a QR code from an image.  
     - Accepts an image input and returns decoded QR / barcode data.  
     - Detailed behavior and parameters defined in the associated action component.

  2. **Compress PDF**  
     - Compresses a PDF file given its URL.  
     - Reduces PDF size while retaining content.  
     - Detailed behavior and parameters defined in the associated action component.

- **Low-Code / No-Code Focus**  
  - Designed as a building block for projects using low-code, no-code, APIs, and automation workflows.

## Pricing
No pricing information is provided in the available content.

## Tags
- no-code  
- automation  
- api-integration