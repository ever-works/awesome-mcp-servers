## MSSQL-Python MCP Server

**Category:** MCP server directories & lists  
**Technology:** Python, Microsoft SQL Server, MCP, FastAPI

### Description
MSSQL-Python MCP Server is a read-only Model Context Protocol (MCP) server for Microsoft SQL Server, implemented in Python. It focuses on secure database access, offering configurable access controls and schema inspection capabilities while preventing write operations.

### Features
- **Read-only MSSQL access** – exposes Microsoft SQL Server data in a strictly read-only manner.  
- **Model Context Protocol (MCP) server** – implements an MCP-compliant server for integration with MCP-compatible clients and tools.  
- **Secure database access** – designed with security in mind to minimize risk when exposing database data to external tools.  
- **Configurable access controls** – allows configuration of what can be accessed, enabling fine-grained control over database visibility.  
- **Schema inspection** – supports inspection of database schema (tables, columns, etc.) without permitting data modification.  
- **Python-based implementation** – written in Python, suitable for extension or integration into Python environments.  
- **FastAPI-powered service** – uses FastAPI to expose the MCP server over HTTP.  
- **Versioned release** – current version indicated as `1.0.1` via project badges.  
- **MCP compatibility** – indicates support for MCP `1.2.0` (per badge).  

### Tech Stack
- **Language:** Python (3.8+)  
- **Database:** Microsoft SQL Server  
- **Framework:** FastAPI  
- **Protocol:** Model Context Protocol (MCP)  

### Licensing & Pricing
- **License:** MIT License (open source)  
- **Pricing:** Free to use under the terms of the MIT License.