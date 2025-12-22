# Redis MCP Server (GongRzhe)

**Category:** MCP Server Directories / Lists  
**Brand:** redis  
**Repository:** https://github.com/GongRzhe/REDIS-MCP-Server  
**License:** MIT

## Overview
A Redis-based Model Context Protocol (MCP) server that lets LLMs interact with Redis key–value stores through standardized tools. It is intended for database-style operations and caching within LLM workflows and is also mirrored into the official `modelcontextprotocol/servers` repository.

## Features
- **MCP-compliant Redis server** for integrating Redis operations into LLM workflows via standardized tools.
- **Key–value operations** on Redis, enabling LLMs to read and write data in a Redis database.
- **Expiration / TTL management** for keys, allowing control over how long cached or stored values persist.
- **Pattern-based key listing**, such as listing keys matching patterns (e.g., prefixes / wildcards) to help LLMs discover relevant data.
- **Database operations for caching** and general Redis-backed storage scenarios in LLM applications.
- **Node.js-based implementation** (via `package.json` and `node_modules`).
- **Containerization support** with a provided `Dockerfile` for building images.
- **Docker Compose configuration** (`docker-compose.yml`) to help run the server (and related services) in a containerized environment.
- **Included in the official MCP servers collection**, pushed to `modelcontextprotocol/servers/tree/main/src/redis`.

## Pricing
- **Open source, MIT-licensed** – free to use, modify, and distribute under the terms of the MIT license.