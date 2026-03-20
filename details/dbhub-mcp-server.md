## Overview

DBHub is a zero-dependency, token-efficient MCP server that provides universal database access through a single unified interface. It supports multiple database systems including PostgreSQL, MySQL, SQL Server, MariaDB, and SQLite, making it an ideal tool for AI assistants to interact with various database backends.

## Features

- **Universal Database Support**: Single interface for PostgreSQL, MySQL, SQL Server, MariaDB, and SQLite
- **MCP Tools Implementation**: Provides execute_sql with transaction support for running SQL queries
- **Schema Exploration**: search_objects tool for discovering and exploring database schemas
- **Token Efficient**: Optimized for minimal token usage in AI interactions
- **Zero Dependencies**: No additional dependencies required for core functionality
- **Transaction Support**: Full support for database transactions ensuring data integrity

## Use Cases

- Database administration through AI assistants
- Schema exploration and documentation
- Query execution and data analysis
- Cross-database operations
- Database migration and synchronization

## Technical Details

DBHub implements the Model Context Protocol standard, providing tools that can be called by MCP-compatible clients like Claude Desktop, Cursor, VS Code, and other AI assistants. The server handles connection management, query execution, and result formatting automatically.