# Qovery MCP Server

[Qovery MCP Server](https://www.qovery.com/docs/copilot/mcp-server) is a Model Context Protocol server that enables AI assistants like Claude to interact with Qovery infrastructure using natural language.

## Features
- **Natural Language Infrastructure Control**: Deploy and manage applications, environments, and services through conversational AI.
- **Kubernetes Management**: Manage Kubernetes clusters across AWS, GCP, Azure, and On-Premise environments.
- **Multi-Cloud Support**: Works with AWS, GCP, Azure, and On-Premise infrastructure.
- **Read-Only and Read-Write Modes**: Configurable access levels based on organization settings and API token permissions.
- **Environment Management**: Create, clone, and manage multiple environments.
- **Application Deployment**: Deploy, restart, scale, and manage applications and services.
- **Troubleshooting**: Access logs, debug issues, and get recommendations.
- **MCP Registry Published**: Available in the official MCP Registry as `com.qovery/mcp-server`.

## Setup
1. Generate a Qovery API token from the Qovery Console (Settings -> API Tokens).
2. Configure your MCP client with the server URL: `https://mcp-api-ai.qovery.com/mcp?token={your_token}`
3. Authenticate by providing your API token in the conversation.

## Transport
- **Type**: Streamable HTTP
- **URL**: `https://mcp-api-ai.qovery.com/mcp?token={qovery_token}`

## Pricing
Qovery MCP Server is included with your Qovery subscription. Requires Qovery AI Copilot activation by organization administrators.

## Category
cloud-devops-mcp-servers

## Tags
mcp, kubernetes, cloud, devops, ai-copilot, infrastructure, aws, gcp, azure, on-premise
