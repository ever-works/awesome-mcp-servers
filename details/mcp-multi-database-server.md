## Overview

MCP Multi-Database Server provides a unified Model Context Protocol interface for connecting AI assistants to multiple database systems including SQLite, SQL Server, and PostgreSQL through a single, consistent API.

## Supported Databases

### SQLite
- Embedded database support
- File-based databases
- In-memory databases
- Zero configuration
- Perfect for development and testing

### SQL Server
- Microsoft SQL Server support
- Azure SQL Database
- SQL Server Express
- Always Encrypted support
- Windows and Linux deployment

### PostgreSQL
- Open-source RDBMS
- Advanced SQL features
- JSONB support
- Full-text search
- Cloud provider compatibility

## Features

### Unified Interface
- Single API for all databases
- Consistent query syntax
- Standardized error handling
- Unified connection management

### Database Operations
- Execute SQL queries
- Schema exploration
- Table and index management
- Data import/export
- Transaction support

### Cross-Database Features
- Database comparison
- Schema migration
- Data synchronization
- Query translation hints

### NPM Package
- Easy installation via npm
- Simple configuration
- Quick deployment with npx
- Version management

## Use Cases

- Multi-database application development
- Database migration projects
- Cross-platform data analysis
- Development environment setup
- Testing across databases
- Database comparison and auditing
- Data integration workflows

## Connection Management

### Connection Strings
- Support for standard connection string formats
- Environment variable configuration
- Secure credential management
- Connection pooling

### Authentication
- Username/password authentication
- Windows authentication (SQL Server)
- IAM authentication (cloud databases)
- SSL/TLS encrypted connections

## Installation

```bash
npm install mcp-database-server
```

Or run directly:
```bash
npx mcp-database-server
```

## Configuration

Simple configuration file supporting:
- Multiple database connections
- Per-database settings
- Query timeout configuration
- Connection pool sizes
- Logging preferences

## Technical Implementation

Built with Node.js using native database drivers:
- better-sqlite3 for SQLite
- tedious for SQL Server  
- pg for PostgreSQL

Provides consistent abstraction layer while preserving database-specific features.

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Works with local databases and cloud-hosted instances.

## Performance

- Connection pooling for efficiency
- Prepared statements
- Batch operations support
- Streaming for large result sets
- Query result caching