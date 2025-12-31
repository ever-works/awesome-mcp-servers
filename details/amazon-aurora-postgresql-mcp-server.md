# Amazon Aurora PostgreSQL MCP Server

**Category:** Database & Messaging MCP Servers  
**Vendor:** Amazon Web Services  
**Website:** https://catalog.redhat.com/en/categories/ai/mcpservers  
**Source / Docs:** https://github.com/awslabs/mcp/tree/main/src/postgres-mcp-server  
**Container Image:** https://quay.io/repository/mcp-servers/awslabs/postgres-mcp-server

## Overview
The Amazon Aurora PostgreSQL MCP Server is a Model Context Protocol (MCP) server that exposes PostgreSQL database operations on Amazon Aurora PostgreSQL through the AWS RDS Data API. It enables MCP-enabled tools and agents to perform structured data access and management against Aurora PostgreSQL clusters without direct database connectivity.

## Features
- **MCP server implementation for Aurora PostgreSQL**
  - Integrates Aurora PostgreSQL as a data source into MCP-enabled tools and environments.
- **RDS Data API–based access**
  - Uses the AWS RDS Data API to interact with Aurora PostgreSQL clusters, avoiding the need for direct network connections or database drivers from the client environment.
- **PostgreSQL database operations**
  - Supports executing SQL commands and queries against Aurora PostgreSQL (specific operation set defined in the GitHub documentation).
- **Containerized distribution**
  - Distributed as a container image built on Red Hat Universal Base Images for consistent deployment.
- **Integration with AWS environment**
  - Designed to work with Amazon Aurora PostgreSQL on AWS, leveraging standard AWS authentication/credentials (details in the project documentation).
- **Official Integrations–based implementation**
  - Based on the "Official Integrations" MCP servers repository from AWS Labs, aligning with Model Context Protocol best practices.

## Typical Use Cases
- Allowing AI agents to query and manage structured data stored in Aurora PostgreSQL.
- Running SQL-based analytics or lookups from MCP-compatible tools against Aurora PostgreSQL.
- Providing controlled, API-based database access where direct database connectivity is restricted.

## Pricing
- No pricing information is provided in the source content. (Usage costs, if any, are determined by AWS services such as Aurora PostgreSQL and RDS Data API; consult AWS pricing documentation.)
