# Amazon ElastiCache / MemoryDB for Valkey MCP Server

## Overview
An AWS Labs Model Context Protocol (MCP) server that connects to Amazon ElastiCache and MemoryDB for Valkey datastores, enabling agents and tools to perform Valkey data structure and caching operations via MCP.

- **Category:** Database & Messaging MCP Servers  
- **Vendor / Brand:** Amazon Web Services  
- **Primary Use Case:** Operate on Valkey key-value data structures (including advanced types) from MCP-compatible clients/tools.

## Features

### Core Capabilities
- Integrates MCP with Valkey-compatible datastores, including Amazon ElastiCache and Amazon MemoryDB for Valkey.
- Exposes Valkey commands as MCP tools so agents can read and manipulate cached and persisted data.

### Supported Data Types & Operations
- **Strings**  
  - Store and retrieve values.  
  - Append to existing values.  
  - Increment and decrement numeric values.  
  - Get and set ranges (substrings).  
  - Retrieve length and other common string operations.

- **Lists**  
  - Manage list collections.  
  - Push elements (e.g., to head/tail).  
  - Pop elements from lists.

- **Sets & Sorted Sets**  
  - Store items in sets and sorted sets.  
  - Retrieve members from sets.

- **Hashes**  
  - Store key–value pairs in hash structures.  
  - Retrieve items from hashes.  
  - Check for existence of specific fields.  
  - Increment values of hash fields.

- **Streams**  
  - Store items/events in streams.  
  - Retrieve items from streams.  
  - Trim streams to control size.

- **Bitmaps**  
  - Perform bitwise operations on strings acting as bitmaps.

- **JSON**  
  - Store JSON documents.  
  - Retrieve JSON values with path-based access.

- **HyperLogLog**  
  - Store elements in HyperLogLog structures.  
  - Estimate and count cardinalities using HyperLogLog.

### Advanced / Operational Features
- **Cluster Support**  
  - Works with both standalone and clustered Valkey deployments.

- **SSL/TLS Security**  
  - Supports configuration of secure connections to Valkey using SSL/TLS.

- **Connection Pooling**  
  - Uses connection pooling by default for efficient connection reuse and reduced overhead.

- **Readonly Mode**  
  - Configurable mode to disable write operations for data safety and audit scenarios.

## Technical & Usage Notes

### Prerequisites
- `uv` installed (from Astral or GitHub).  
- Python 3.10 installed via `uv` (e.g., `uv python install 3.10`).  
- Network access to a Valkey datastore (e.g., Amazon ElastiCache / MemoryDB for Valkey).  
- Optional: AWS-specific connection instructions available in the linked `ELASTICACHECONNECT.md` document.

### Example Configuration (Non-Windows)
- Typical MCP client configuration uses:
  - `command`: `uvx`  
  - `args`: `["awslabs.valkey-mcp-server@latest"]` (plus `"--readonly"` for readonly mode).  
  - `env` variables such as:
    - `VALKEY_HOST` (e.g., `127.0.0.1`)
    - `VALKEY_PORT` (e.g., `6379`)
    - `FASTMCP_LOG_LEVEL` (e.g., `ERROR`)

### Windows Notes
- Windows uses a slightly different MCP configuration format (details continue beyond the provided excerpt).

## Pricing
No pricing or plan information is provided in the available content. The server appears to be an AWS Labs tool; usage costs, if any, would typically derive from the underlying Valkey-compatible services (e.g., Amazon ElastiCache / MemoryDB) rather than the MCP server itself.