## Overview

Roam Research MCP Server connects AI assistants like Claude to Roam Research for seamless data interaction and management. It provides comprehensive access to Roam's powerful graph database for knowledge management.

## Features

### Graph Operations
- Query Roam database using Datalog
- Navigate bidirectional links
- Explore block references
- Access page hierarchies
- Query block attributes

### Data Access
- Read pages and blocks
- Search across entire graph
- Filter by tags and attributes
- Access daily notes
- Retrieve linked references

### Write Operations
- Create new pages
- Add blocks to pages
- Update existing content
- Create block references
- Add attributes and metadata

### Advanced Features
- Datalog query support
- Graph traversal
- Block embedding
- Attribute queries
- Namespace management

## Roam-Specific Capabilities

### Block System
- Hierarchical block structure
- Block references ((block-id))
- Block embeds {{embed: block-id}}
- Block attributes

### Bidirectional Links
- Page linking [[Page Name]]
- Automatic backlinks
- Link graph visualization
- Orphaned page detection

### Attributes
- Key-value attributes
- Attribute queries
- Attribute inheritance
- Custom schemas

## Use Cases

- Research organization and retrieval
- Knowledge graph construction
- Personal knowledge management
- Writing assistance
- Literature review
- Meeting notes management
- Project planning
- Daily journaling automation

## Datalog Queries

Support for Roam's powerful Datalog query language:
- Complex graph queries
- Multi-level traversal
- Attribute-based filtering
- Temporal queries
- Relationship discovery

## Technical Implementation

Integrates with Roam Research API providing standardized MCP interface to Roam's graph database. Handles authentication, rate limiting, and data synchronization.

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Requires Roam Research account and API access token.

## Security

Secure API authentication, encrypted data transmission, and respect for Roam's privacy settings and access controls.