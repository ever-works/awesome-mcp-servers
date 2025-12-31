# Amazon Keyspaces MCP Server

## Overview
The Amazon Keyspaces (for Apache Cassandra) MCP Server is an MCP (Model Context Protocol) server that enables AI assistants (such as Amazon Q) to interact with Amazon Keyspaces or Apache Cassandra databases using natural language. It lets users explore schemas, run CQL SELECT queries, and analyze query performance without manually writing CQL.

- **Category:** Database & Messaging MCP Servers  
- **Vendor/Brand:** Amazon Web Services  
- **Works With:** Amazon Keyspaces (for Apache Cassandra), Apache Cassandra

## Features
- **Schema exploration**  
  - List and explore keyspaces.  
  - View and inspect tables within keyspaces.  
  - Describe table schemas (columns, structure).

- **Query execution**  
  - Run CQL `SELECT` queries against the configured database.  
  - Support for querying specific tables and limiting returned records (e.g., first N rows).

- **Query performance analysis**  
  - Analyze provided CQL queries for performance.  
  - Get feedback on whether a query is efficient.  
  - Receive suggestions for improving query performance.

- **Cassandra compatibility**  
  - Compatible with Amazon Keyspaces (for Apache Cassandra).  
  - Compatible with native Apache Cassandra clusters that support password authentication.

- **Natural-language interaction via MCP**  
  - Exposes schema and query operations via the Model Context Protocol.  
  - Designed to be driven by natural-language prompts from AI assistants.

## Installation

### Prerequisites
- Python 3.10 or 3.11  
- Access to an Amazon Keyspaces instance or an Apache Cassandra cluster that supports password authentication  
- Valid Cassandra login credentials  
- Starfield digital certificate (required when using Amazon Keyspaces)

### Install from PyPI
```bash
pip install awslabs.amazon-keyspaces-mcp-server
```

### Install from Source
1. Clone the repository:
   ```bash
   git clone https://github.com/awslabs/mcp.git
   cd mcp/src/amazon-keyspaces-mcp-server
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```
3. Install the package in editable mode:
   ```bash
   pip install -e .
   ```

## Configuration
Create a `.keyspaces-mcp` directory in your home directory, then create an `env` file inside it with database connection settings.

Example `env` contents:
```bash
# Use Amazon Keyspaces (true) or Apache Cassandra (false)
DB_USE_KEYSPACES=true

# Cassandra configuration (for native Cassandra)
DB_CASSANDRA_CONTACT_POINTS=127.0.0.1
DB_CASSANDRA_PORT=9042
DB_CASSANDRA_LOCAL_DATACENTER=datacenter1
DB_CASSANDRA_USERNAME=
DB_CASSANDRA_PASSWORD=

# Keyspaces configuration (for Amazon Keyspaces)
DB_KEYSPACES_ENDPOINT=cassandra.us-west-2.amazonaws.com
DB_KEYSPACES_REGION=us-west-2
```

## Pricing
No pricing information is provided in the available content. The server is distributed as a Python package (`awslabs.amazon-keyspaces-mcp-server`); usage of Amazon Keyspaces or Apache Cassandra may incur separate database/service costs.