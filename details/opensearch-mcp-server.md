## Overview

The OpenSearch MCP (Model Context Protocol) server provides native capabilities that let AI agents seamlessly perform search, analytics, and vector store operations. The built-in server is fully integrated into OpenSearch with no need to deploy, host, or maintain a separate MCP server.

## Key Features

### Native Integration

- **Built-in Server**: Fully integrated into OpenSearch
- **No Separate Deployment**: No need to deploy, host, or maintain a separate MCP server
- **OpenSearch Security**: Uses OpenSearch security for authentication
- **Consistent Access Control**: Enforces uniform access control across all tools
- **Standard Interface**: Removes need for custom integration code

### Available Tools

- **SearchIndexTool**: Search an index using OpenSearch query DSL
- **ClusterHealthTool**: Basic cluster health information
- **GetIndexStatsTool**: Statistics including document count and performance metrics
- **GetQueryInsightsTool**: Query patterns and performance insights

## AWS Integration

AWS provides MCP server integration templates that handle:

- **Inbound Authentication**: From users to MCP server
- **Outbound Authentication**: From MCP server to OpenSearch
- **OAuth Support**: Enterprise authentication
- **Regional Availability**: Available in specific AWS Regions including US East (N. Virginia)

### Deployment

After deployment, integrate the MCP server with any MCP compatible agent including:
- Amazon Bedrock
- Claude Desktop
- Custom MCP clients
- Other AI platforms

## Use Cases

- Integrating OpenSearch operations into AI applications
- Real-time data streaming from OpenSearch clusters
- Developing tools for managing and querying OpenSearch indices
- Natural language search across enterprise data
- AI-powered analytics and insights
- Vector similarity search for RAG applications

## Security Features

- Built-in OpenSearch security integration
- Consistent authentication across all tools
- Role-based access control (RBAC)
- Enterprise-grade security standards
- Audit logging capabilities

## Technical Architecture

- Fully integrated MCP server within OpenSearch
- Support for OpenSearch Query DSL
- Vector store operations
- Real-time cluster monitoring
- Performance insights and analytics

## Benefits

- Zero additional infrastructure
- Simplified deployment
- Consistent security model
- Standard protocol interface
- Production-ready integration
- Enterprise support

## Regional Availability

Available in AWS Regions:
- US East (N. Virginia)
- Additional regions as deployed

## Integration Templates

AWS provides CloudFormation templates for:
- Authentication setup
- Security configuration
- MCP server deployment
- Amazon Bedrock integration

## Pricing

Part of OpenSearch deployment. No additional cost for MCP server functionality. AWS infrastructure costs apply.