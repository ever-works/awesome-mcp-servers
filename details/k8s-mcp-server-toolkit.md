## Overview

K8s MCP Server Toolkit is a comprehensive Model Context Protocol server that provides AI assistants with secure access to essential Kubernetes CLI tools including kubectl, helm, istioctl, and argocd. It serves as a bridge between language models and Kubernetes cluster management, enabling natural language operations.

## Included Tools

- **kubectl**: Complete Kubernetes command-line interface
- **Helm**: Kubernetes package manager for application deployment
- **istioctl**: Service mesh management with Istio
- **argocd**: GitOps continuous delivery for Kubernetes

## Features

- **Unified Interface**: Access multiple Kubernetes tools through a single MCP server
- **Cloud Provider Support**: Native integration with AWS EKS, Google GKE, and Azure AKS
- **Secure Execution**: Sandboxed command execution with audit logging
- **Multi-Cluster Management**: Switch between clusters seamlessly
- **Helm Chart Operations**: Install, upgrade, and manage Helm releases
- **Istio Service Mesh**: Configure and monitor service mesh components
- **GitOps with ArgoCD**: Manage applications using GitOps principles
- **Authentication Integration**: Support for cloud provider authentication

## Use Cases

- Kubernetes cluster management through AI
- Application deployment with Helm charts
- Service mesh configuration and troubleshooting
- GitOps workflow automation with ArgoCD
- Multi-cloud Kubernetes operations
- Debugging and diagnostics
- Security audits and compliance checks

## Cloud Provider Integration

**AWS EKS**: Direct integration with AWS IAM for authentication
**Google GKE**: Support for GCP service accounts and workload identity
**Azure AKS**: Integration with Azure AD and managed identities

## Technical Implementation

Containerized deployment ensures consistent tool versions and dependencies. The server handles authentication, context switching, and command execution while providing detailed output and error handling.

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Supports configuration through environment variables and kubeconfig files.