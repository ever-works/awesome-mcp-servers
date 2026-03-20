## Overview

pgMCP is an innovative Model Context Protocol server that enables natural language querying of PostgreSQL databases. It automatically translates plain English questions into optimized SQL queries, making database access intuitive for AI assistants.

## Features

### Natural Language Interface
- Ask questions in plain English
- Automatic SQL generation
- Context-aware query building
- Multi-table join support
- Aggregate function understanding

### Intelligent Query Translation
- Semantic understanding of database schema
- Relationship inference
- Ambiguity resolution
- Query optimization
- Error correction suggestions

### Schema Understanding
- Automatic schema analysis
- Table relationship mapping
- Column type awareness
- Foreign key detection
- Index recognition

### Query Optimization
- Generated queries are optimized
- Proper index usage
- Efficient joins
- Minimal data scanning
- Query plan analysis

## Example Queries

**Natural Language:**
- "Show me all customers who placed orders last month"
- "What are the top 5 products by revenue?"
- "Find users who haven't logged in for 30 days"
- "Calculate average order value by region"

**Automatic Translation:**
The server understands the intent and generates appropriate SQL with proper joins, aggregations, and filters.

## Use Cases

- Business intelligence queries
- Data exploration and analysis
- Report generation
- Dashboard data retrieval
- Ad-hoc data requests
- Database debugging
- Schema understanding
- Learning SQL through examples

## Advanced Capabilities

### Contextual Queries
- Follow-up questions use previous context
- Reference previous results
- Iterative refinement
- Conversation-based querying

### Complex Operations
- Window functions
- CTEs (Common Table Expressions)
- Subqueries
- Lateral joins
- JSON operations

### Safety Features
- Read-only mode by default
- Query validation
- Cost estimation
- Timeout protection
- Result size limiting

## Technical Implementation

Leverages AI models to understand natural language and database schemas, generating optimized PostgreSQL-specific SQL queries with proper syntax and best practices.

## Configuration

```json
{
  "database": {
    "host": "localhost",
    "port": 5432,
    "database": "mydb",
    "user": "user",
    "password": "***"
  },
  "readOnly": true,
  "maxResults": 1000
}
```

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Works with any PostgreSQL database including cloud-hosted instances.

## Performance

- Query caching
- Schema caching
- Optimized SQL generation
- Connection pooling
- Streaming results