# mcp-server-ipinfo

**Category:** Data Access & Integration MCP Servers  
**Brand:** briandconnelly  
**License:** MIT  
**Source:** https://github.com/briandconnelly/mcp-server-ipinfo

## Overview

`mcp-server-ipinfo` is a Model Context Protocol (MCP) server that exposes IP address geolocation and network information using the ipinfo.io service. It is intended to be integrated into MCP-compatible clients (such as AI assistants) to look up details about IP addresses and related network metadata.

## Features

- **MCP server implementation**
  - Implements a server compatible with the Model Context Protocol.
  - Can be registered and used as a tool/server within MCP-enabled environments.

- **IP geolocation via ipinfo.io**
  - Retrieves geolocation data for IP addresses from the ipinfo.io API.
  - Designed to surface IP-based information such as location and network details (per the ipinfo.io service capabilities).

- **Network information lookup**
  - Provides network-related metadata for IP addresses (e.g., ISP/organization, network/ASN details, etc., as supported by ipinfo.io).

- **Simple setup**
  - Distributed as a Python project (`pyproject.toml` present) for straightforward installation.
  - Configuration and source code organized under `src/mcp_server_ipinfo`.

- **Open source**
  - Source code available on GitHub for inspection, customization, or extension.
  - Licensed under the MIT license, allowing permissive use and modification.

## Pricing

- The `mcp-server-ipinfo` software itself is open source under the MIT license and is available for free.
- Use of the underlying ipinfo.io service may be subject to ipinfo.io’s own pricing or rate limits (not defined in this repository).