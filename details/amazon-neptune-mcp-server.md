## Amazon Neptune MCP Server

**Category:** Database & Messaging MCP Servers  
**Brand:** Amazon Web Services  
**Website:** https://awslabs.github.io/mcp/servers/amazon-neptune-mcp-server

### Description
Amazon Neptune MCP Server is an MCP-compatible server that connects MCP clients (such as AI tools or editors) to Amazon Neptune. It supports running graph queries against Neptune Database and Neptune Analytics using openCypher and Gremlin, and exposes status and schema information for the configured graph.

### Features
- **Query Execution**
  - Run openCypher queries against Amazon Neptune Database
  - Run Gremlin queries against Amazon Neptune Database
  - Run openCypher queries against Amazon Neptune Analytics
  - Supports both read-only and mutating queries (behavior controlled by IAM permissions)

- **Schema Access**
  - Retrieve the schema of the configured graph
  - Schema returned as a text string for inspection or further processing by clients

- **Status Reporting**
  - Check whether the graph is "Available" or "Unavailable" to the server
  - Useful for verifying connectivity between the MCP server and the Neptune instance

- **AWS Integration Requirements**
  - Uses AWS CLI credentials and an AWS_PROFILE with access to Amazon Neptune
  - Works with at least one Amazon Neptune Database or Neptune Analytics graph
  - Relies on IAM permissions to control:
    - Access to Amazon Neptune
    - Ability to query Neptune (including data-plane operations)
  - Requires network access from the MCP server host to the Neptune endpoint:
    - Neptune Database typically in a private VPC (requires VPC/private access)
    - Neptune Analytics can be accessed via a public endpoint (if configured) or a private endpoint

- **Client Configuration & Runtime**
  - Distributed as a Python-based tool executable via `uvx` / `uv`
  - Configurable as an MCP server in compatible clients (e.g., via `mcpServers` JSON configuration)
  - Uses environment variables for configuration, including:
    - `NEPTUNE_ENDPOINT` – Neptune endpoint in the required format
    - `FASTMCP_LOG_LEVEL` – log verbosity (e.g., `INFO`)
  - Supports stdio-based MCP communication

- **Cross-Platform Setup**
  - Example configuration for general environments using `uvx awslabs.amazon-neptune-mcp-server@latest`
  - Windows-specific configuration example using `uv tool run --from awslabs.amazon-neptune-mcp-server@latest awslabs.amazon-neptune-mcp-server.exe`

### Prerequisites
- Installed `uv` (Astral tool)  
- Python 3.10 installed via `uv python install 3.10`  
- AWS CLI configured with valid credentials and AWS profile with Neptune access  
- Network connectivity to the relevant Neptune Database or Neptune Analytics endpoint

### Installation & Configuration (Summary)
- Install `uv` and Python 3.10.
- Configure AWS CLI and IAM permissions for Neptune access.
- In your MCP client configuration, add an MCP server entry that:
  - Uses `uvx` (or `uv tool run` on Windows) to run `awslabs.amazon-neptune-mcp-server@latest`.
  - Sets `NEPTUNE_ENDPOINT` and `FASTMCP_LOG_LEVEL` in the environment.

### Pricing
No pricing information is provided in the available content. Product usage costs are likely governed by standard AWS Neptune and related AWS service pricing.
