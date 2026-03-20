## Overview

The Kubernetes MCP Server is a native Go implementation that interacts directly with the Kubernetes API server, providing comprehensive cluster management capabilities through the Model Context Protocol. Unlike kubectl wrappers, this server provides native API integration for superior performance and reliability.

## Features

- **Native Go Implementation**: Direct Kubernetes API server integration without kubectl dependency
- **Multi-Cluster Support**: Manage multiple Kubernetes clusters simultaneously
- **OpenShift Compatibility**: Full support for OpenShift-specific resources and features
- **Complete CRUD Operations**: Create, read, update, and delete Kubernetes resources
- **Resource Discovery**: Automatic discovery of available resource types
- **Namespace Management**: Organize and manage namespaces across clusters
- **Pod Operations**: Advanced pod management including logs, exec, and port-forwarding
- **Deployment Management**: Scale, rollout, and rollback deployments
- **Service Discovery**: Query and manage Kubernetes services and endpoints

## Available Packages

- Native binary for Linux, macOS, and Windows
- NPM package for Node.js projects
- Python package via pip
- Container/Docker image for containerized deployments

## Use Cases

- Kubernetes cluster administration
- Application deployment and management
- Troubleshooting and debugging
- Resource optimization and scaling
- Multi-cluster operations
- GitOps workflow automation
- Disaster recovery
- Cost optimization

## Technical Implementation

Built using the official Kubernetes client-go library, ensuring compatibility with all Kubernetes versions and distributions. Supports multiple authentication methods including kubeconfig, service accounts, and cloud provider credentials.

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Supports loading kubeconfig from multiple sources and environment-based cluster selection.

## Security

Implements Kubernetes RBAC (Role-Based Access Control) for fine-grained permissions, supports read-only mode for safe operations, and provides audit logging for all cluster interactions.