## Amazon MQ MCP Server

**Category:** Database & Messaging MCP Servers  
**Brand:** Amazon Web Services

A Model Context Protocol (MCP) server that lets MCP-based agents and other MCP clients create, configure, and manage Amazon MQ brokers (RabbitMQ and ActiveMQ) through standardized tools.

---

### Features

- **MCP bridge for Amazon MQ**  
  - Exposes Amazon MQ management capabilities as MCP tools.  
  - Allows generative AI models and MCP clients to manage RabbitMQ and ActiveMQ brokers.

- **Broker lifecycle management**  
  - Create new Amazon MQ brokers (RabbitMQ and ActiveMQ).  
  - Reboot existing brokers.  
  - Update brokers (e.g., apply configuration changes or upgrades where supported).  
  - List and describe existing brokers.

- **Configuration management**  
  - Create and manage broker configurations.  
  - Configure broker settings and parameters through MCP tools.

- **Security and access control**  
  - Uses AWS IAM profiles on the host for authorization to AWS accounts.  
  - Supports read-only access via `AmazonMQReadOnlyAccess`.  
  - Supports mutating tools (create/update/delete) with `AmazonMQFullAccess`.  
  - Implements automatic resource tagging so the MCP server can only modify resources it created.  
  - Protects existing Amazon MQ resources that were not created by the MCP server from unintended modification.

- **Amazon MQ broker coverage**  
  - Works with Amazon MQ for RabbitMQ brokers at the broker level.  
  - Works with Amazon MQ for ActiveMQ brokers.

- **Client integration**  
  - Can be configured as an external MCP server for MCP-compatible clients, such as Amazon Q Developer and other MCP-based agents.  
  - Runs via `uvx` using the `awslabs.amazon-mq-mcp-server` package.

- **Secure operations model**  
  - Relies on AWS profiles configured on the host for credential management.  
  - Encourages least-privilege IAM role configuration.

---

### Prerequisites

- `uv` installed (from Astral).  
- Python 3.10 installed via `uv python install 3.10`.  
- An AWS account with permissions to create and manage Amazon MQ resources.  
- An AWS profile configured on the host, typically assuming a role with `AmazonMQReadOnlyAccess` or `AmazonMQFullAccess` as needed.

---

### Setup & Installation (Summary)

- Configure IAM:
  - Create an IAM role with `AmazonMQReadOnlyAccess` for read operations, or `AmazonMQFullAccess` for mutating tools.
  - Configure an AWS profile on the host that assumes this role.

- Install & run:
  - Use `uvx` with `awslabs.amazon-mq-mcp-server@latest` as the command.  
  - Set `AWS_PROFILE` in the environment for the MCP server process.

- Client configuration example (Amazon Q Developer):
  - Add an entry for `awslabs.amazon-mq-mcp-server` in the MCP client configuration (e.g., `~/.aws/amazonq/mcp.json`) with:
    - `command`: `uvx`  
    - `args`: `["awslabs.amazon-mq-mcp-server@latest"]`  
    - `env`: includes `AWS_PROFILE`.

---

### Pricing

- No specific pricing information is provided for the Amazon MQ MCP Server itself.  
- Standard AWS charges for Amazon MQ resources (RabbitMQ and ActiveMQ brokers) apply according to your AWS account’s Amazon MQ pricing.