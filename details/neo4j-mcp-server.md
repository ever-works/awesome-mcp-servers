# Neo4j MCP Server

## Overview
The Neo4j MCP Server is a Model Context Protocol (MCP) server for the Neo4j graph database. It exposes Neo4j schema and supports read/write Cypher operations, along with a graph-database-backed memory layer intended for use with LLMs and agent frameworks. It is developed under the Neo4j Labs program and maintained by the Neo4j Field GenAI team and the community.

## Features
- **MCP server for Neo4j**
  - Implements a Model Context Protocol server interface for integrating Neo4j into MCP-compatible tools and agents.

- **Neo4j graph database integration**
  - Connects directly to a Neo4j graph database instance.
  - Uses Neo4j’s native graph model for storing and retrieving structured data.

- **Schema exposure**
  - Exposes the Neo4j database schema to clients.
  - Enables tools and agents to inspect node labels, relationships, and properties for better context-aware querying.

- **Read Cypher operations**
  - Supports executing Cypher read queries against Neo4j.
  - Allows retrieval of graph data (nodes, relationships, paths, and properties) via MCP.

- **Write Cypher operations**
  - Supports executing Cypher write queries.
  - Enables creating, updating, and deleting graph data through MCP.

- **Graph-backed memory layer**
  - Provides a memory layer built on top of Neo4j.
  - Intended for storing and retrieving contextual information or long-term memory for LLM-based agents.
  - Leverages graph structure for linking and organizing memories.

- **Neo4j Labs project**
  - Developed under the Neo4j Labs program by the Neo4j Field GenAI team.
  - Actively developed with new and experimental features.
  - No formal SLAs or guarantees around backwards compatibility or deprecation.

## Pricing
- No explicit pricing information is provided in the available content.
- Distributed as source code on GitHub; see the repository’s `LICENSE.txt` for licensing and usage terms.