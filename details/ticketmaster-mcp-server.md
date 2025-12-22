## Ticketmaster MCP Server

**Category:** MCP servers / Directories & Lists  
**Source:** [GitHub – delorenj/mcp-server-ticketmaster](https://github.com/delorenj/mcp-server-ticketmaster)

### Description
Ticketmaster MCP Server is a Model Context Protocol (MCP) server that integrates with the Ticketmaster Discovery API to enable LLMs and MCP-compatible tools to search and retrieve events, venues, and attractions from Ticketmaster.

### Features
- **Model Context Protocol server**
  - Implements MCP so it can be used with MCP-compatible LLM tools and environments.
- **Ticketmaster Discovery API integration**
  - Connects directly to the Ticketmaster Discovery API.
- **Event discovery**
  - Provides tools to discover Ticketmaster events via the Discovery API.
- **Venue discovery**
  - Supports retrieval and search of venues.
- **Attraction discovery**
  - Supports retrieval and search of attractions (e.g., artists, teams, performers).
- **Tool-based access for LLMs**
  - Exposes discovery capabilities as tools that LLMs can call in-context.
- **Configuration via environment file**
  - Includes an example `.env` file (`.env.example`) for configuring required environment variables (e.g., API credentials).
- **Containerization support**
  - Includes a `Dockerfile` for containerized deployment.
- **TypeScript/Node.js project structure**
  - Uses `package.json`, `tsconfig.json`, and `package-lock.json` for dependency and build management.
- **MCP registry metadata**
  - Provides a `smithery.yaml` configuration for use with Smithery and similar MCP tooling/registries.

### Technical Details
- **Protocol:** Model Context Protocol (MCP)
- **Primary API:** Ticketmaster Discovery API
- **Implementation:** TypeScript/Node.js (based on repo structure)
- **Distribution:** Source code available on GitHub

### Pricing
- No pricing information or commercial plans are specified in the provided content.  
- Usage terms are defined by the LICENSE file in the GitHub repository (license type not specified in the excerpt).