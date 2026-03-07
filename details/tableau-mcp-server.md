## Overview

Tableau's official MCP Server helps agents see and understand data. The Model Context Protocol (MCP) is a standard that gives large language models (LLMs) a universal way to access external tools and data sources.

## Key Features

- **Natural Language Queries**: Chat with an LLM and ask it questions about your own Tableau environment and data directly
- **Data Retrieval**: Query and retrieve data from Tableau Server or Tableau Cloud
- **Published Data Sources**: Works with Published Data Sources for consistent data access
- **Metadata API Access**: Requires Metadata API to be enabled on Tableau Server for certain tools

## Capabilities & Limitations

- Can query and retrieve data but can't create new visualizations or dashboards directly in Tableau through MCP
- Currently only works with Published Data Sources, limiting flexibility for ad-hoc analysis
- If using Tableau Server, Metadata API access needs to be enabled for certain tools to work

## Community Implementations

Besides the official Tableau MCP server, there are community-developed implementations including:
- LokiMCPUniverse/tableau-mcp-server - A Model Context Protocol server for integrating Tableau with GenAI applications
- asklokesh/tableau-mcp-server - Community MCP server for Tableau

## Use Cases

- Natural language querying of Tableau data through AI assistants like Claude
- AI-powered data analysis without requiring complex API calls
- Lakers data analysis and sports analytics
- Business intelligence through conversational AI

## Integration

Works with Claude, Cursor, and other MCP-compatible AI tools.