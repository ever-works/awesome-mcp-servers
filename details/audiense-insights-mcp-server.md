## Audiense Insights MCP Server

**Category:** Business & Commerce MCP Servers  
**Slug:** audiense-insights-mcp-server  
**Source:** https://github.com/AudienseCo/mcp-audiense-insights  
**License:** Apache-2.0  
**Status:** Archived (repository is read-only)

### Overview
Audiense Insights MCP Server is a Model Context Protocol (MCP) server that lets Claude and other MCP-compatible clients access and work with data from an Audiense Insights account. It focuses on exposing demographic, cultural, influencer, and content engagement analytics derived from Audiense audience intelligence reports.

### Features
- **MCP-based server implementation**
  - Implements the Model Context Protocol to integrate with MCP-compatible AI clients (e.g., Claude Desktop with MCP).
  - Exposes Audiense Insights data as tools/resources that AI agents can call programmatically.

- **Audiense Insights integration**
  - Connects to an existing Audiense Insights account.
  - Uses Audiense reports as the main data source for audience analytics.

- **Demographic analysis access**
  - Surfaces demographic breakdowns (e.g., age, gender, location) derived from Audiense Insights reports to AI agents.

- **Cultural and interest analysis**
  - Exposes cultural affinities and interests identified by Audiense (e.g., lifestyle, media preferences, topics) for a given audience.

- **Influencer analysis**
  - Provides access to influencer data from Audiense reports (e.g., key accounts or profiles with high relevance/affinity to the audience).

- **Content engagement analysis**
  - Makes content engagement metrics and patterns available to AI agents, enabling analysis of what content resonates with specific audiences.

- **AI workflow enablement**
  - Designed so AI agents can:
    - Query and summarize Audiense audience segments.
    - Generate audience personas using demographics and interests.
    - Suggest influencers based on affinity data.
    - Propose content topics and formats based on engagement insights.

- **Docker support**
  - Includes a `Dockerfile` for containerized deployment of the MCP server.

- **Node.js project structure**
  - Distributed as a Node.js package (with `package.json` and `package-lock.json`).
  - Includes Jest configuration (`jest.config.js`) for testing.

### Technical Notes
- **Compatibility:** Built for Claude and other MCP-compatible clients.
- **Source structure:** Main implementation under `src/` in the GitHub repository.

### Pricing
No pricing information is provided in the available content. The repository is open source under the Apache-2.0 license; any commercial terms for the underlying Audiense Insights account are not described in the referenced material.