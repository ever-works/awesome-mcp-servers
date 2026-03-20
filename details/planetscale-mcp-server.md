## Overview

PlanetScale MCP support enables AI tools like Claude, Cursor, or Zed to directly access read-only database information to answer questions about your database. The PlanetScale CLI provides commands to configure and run the MCP server with intelligent query execution and automatic replica routing.

## Features

- **Read-Only Access**: Secure database queries without modification risk
- **Natural Language Queries**: Ask questions like "How many users do I have in North Carolina?"
- **Database Organizations**: Access to database schemas, branches, and performance insights
- **Query Insights**: Data available via PlanetScale dashboard and MCP server for informed application updates
- **Automatic Replica Routing**: Intelligent query execution across database replicas
- **Human Confirmation**: Schema changes require explicit approval
- **AI Tool Compatibility**: Works with Claude Code, Cursor, Zed, and other MCP-compatible tools

## PlanetScale Platform

PlanetScale is a serverless database platform built on Vitess, a database clustering system for MySQL, offering:

- **Database Branching**: Create development branches like Git
- **Non-Blocking Schema Changes**: Deploy schema updates without downtime
- **Horizontal Scaling**: Scale MySQL databases automatically
- **Launch in Seconds**: No limitations on scalability
- **Vitess-Powered**: Enterprise-grade database cluster management

## CLI Commands

```bash
# Install MCP server for specific AI tool
pscale mcp install --target <claude|cursor|zed>

# Run MCP server
pscale mcp server
```

## Use Cases

- Database analytics and insights from AI assistants
- Schema exploration and documentation
- Query optimization recommendations
- Data analysis and reporting
- Database health monitoring through natural language

## Pricing

Part of PlanetScale platform. Multiple pricing tiers available including free tier for development.