## Ramp MCP

### Description
Ramp MCP is an open-source Model Context Protocol (MCP) server that connects LLM agents to Ramp’s Developer API. It retrieves and analyzes Ramp financial and spend data by loading it into an in-memory SQLite database via a simple ETL pipeline, enabling structured querying and analysis within MCP-compatible clients. By default, it uses Ramp’s demo environment, with an option to target production via configuration.

### Features
- **Ramp Developer API integration**  
  - Connects to Ramp’s Developer API for accessing company spend and financial data.  
  - Supports switching environments via `RAMP_ENV` (default: demo; can be set to `prd`).

- **Model Context Protocol (MCP) server**  
  - Exposes Ramp data and operations as MCP tools for use by LLM agents.  
  - Designed for use in MCP-compatible clients (e.g., AI agents/editors that support MCP).

- **Ephemeral in-memory database**  
  - Implements a simple ETL pipeline that loads retrieved Ramp data into an ephemeral SQLite database in memory.  
  - Intended to work around token and input size limitations by enabling structured querying instead of passing raw data.  
  - Database exists only for the duration of the session/process.

- **Database tools (MCP tools)**  
  - Tools for setting up the ephemeral database.  
  - Tools for processing and transforming retrieved data into database tables.  
  - Query tools to run SQL (or equivalent) against the in-memory SQLite database.  
  - Tools to delete/tear down the ephemeral database when no longer needed.

- **Data analysis support**  
  - Enables LLM-driven analysis of spend and financial data via database queries.  
  - Suitable for analytical tasks within the constraints of API and MCP client limits.  
  - Note: very large datasets may not be fully processable due to API response and/or MCP client limitations.

- **Open-source and configurable**  
  - Source available on GitHub under the MIT license.  
  - Configuration via environment variables (e.g., `RAMP_ENV`).

### Pricing
- Not specified; the project is open-source and licensed under the **MIT license**. Any usage-based or account-related costs for Ramp’s Developer API are not described in the provided content.