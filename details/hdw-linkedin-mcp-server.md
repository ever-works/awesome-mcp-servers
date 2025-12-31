# HDW LinkedIn MCP Server

## Overview
HDW LinkedIn MCP Server is a Model Context Protocol (MCP) server that integrates HorizonDataWave with LinkedIn-style profile data and account management. It is based on the `anysite-mcp-server` implementation, providing comprehensive access to LinkedIn-type data and functionalities via LLM tools and APIs.

- **Category:** Data-access & integration MCP servers  
- **Source:** Open-source (MIT license)  
- **Repository:** https://github.com/horizondatawave/hdw-mcp-server

## Features

### LinkedIn-style Data Access
- Provides access to LinkedIn-style profile data.  
- Supports retrieval of user-related information using an underlying API (Anysite/LinkedIn-like API).  
- Designed for use within LLM tools via the Model Context Protocol.

### Account & Profile Management
- Enables management of user accounts in addition to data retrieval.  
- Focused on LinkedIn-like account and profile operations (e.g., handling account-level data and settings through the MCP server).

### MCP Server Capabilities
- Implements the Model Context Protocol so LLMs can call tools to:
  - Query profile and contact-like data.  
  - Perform account-related operations via defined MCP tools.
- Intended for integration with LLM environments that support MCP servers (e.g., Claude desktop / MCP-compatible clients).

### Integration Layer
- Integrates HorizonDataWave with a LinkedIn-style data source through an MCP server abstraction.  
- Uses an external API (originally the Anysite API in the reference project) to provide social/contact data and account functionality to downstream applications.

### Open Source & Licensing
- Distributed under the MIT license.  
- Source code available on GitHub for customization and self-hosting.

## Pricing
No pricing information is provided in the available content. The project appears to be open-source under the MIT license, which generally allows free use, modification, and distribution, subject to the license terms.