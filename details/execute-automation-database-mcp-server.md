## Overview

Execute Automation Database MCP Server provides a universal interface for managing multiple database types through the Model Context Protocol. It enables AI assistants to work seamlessly with SQLite, SQL Server, PostgreSQL, and MySQL.

## Supported Databases

### SQLite
- Embedded database support
- File-based databases
- In-memory databases
- Zero configuration
- Perfect for development

### SQL Server
- Microsoft SQL Server
- Azure SQL Database
- Managed instances
- Always Encrypted support

### PostgreSQL
- PostgreSQL 12+
- Amazon RDS PostgreSQL
- Azure Database for PostgreSQL
- Google Cloud SQL PostgreSQL

### MySQL
- MySQL 5.7+
- MySQL 8.0
- Amazon RDS MySQL
- Azure Database for MySQL
- MariaDB compatibility

## Features

### Unified Interface
- Single API for all databases
- Consistent query syntax
- Standardized error handling
- Common feature set

### Database Operations
- Execute SQL queries
- Parameterized queries
- Transaction management
- Stored procedure calls
- Batch operations

### Schema Management
- Create and alter tables
- Index management
- Constraint handling
- View management
- Schema exploration

### Data Operations
- CRUD operations
- Bulk insert/update
- Data export
- Data import
- Data validation

## NPM Package

Available via npm for easy deployment:
```bash
npm install @executeautomation/mcp-database-server
```

Run with npx:
```bash
npx @executeautomation/mcp-database-server
```

## Use Cases

- Multi-database application management
- Database migration between platforms
- Cross-database queries and analysis
- Development and testing
- Database administration
- Data integration
- Backup and recovery
- Performance analysis

## Connection Management

### Connection Strings
- SQLite: File path or :memory:
- SQL Server: Server, database, authentication
- PostgreSQL: Host, port, database, credentials
- MySQL: Host, port, database, credentials

### Connection Pooling
- Efficient connection reuse
- Configurable pool size
- Connection timeout handling
- Automatic reconnection

## Security

- Parameterized queries (SQL injection prevention)
- Encrypted connections (TLS/SSL)
- Credential encryption
- Role-based access
- Audit logging

## Technical Implementation

Built with TypeScript and dedicated database drivers:
- better-sqlite3 for SQLite
- mssql for SQL Server
- pg for PostgreSQL
- mysql2 for MySQL/MariaDB

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Simple configuration with connection strings.

## Performance

- Optimized query execution
- Connection pooling
- Query result caching
- Streaming for large results