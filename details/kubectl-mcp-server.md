## Overview

kubectl MCP Server enables controlling Kubernetes infrastructure through natural language commands. Available via NPM and pip, it provides comprehensive cluster management capabilities including debugging, cost optimization, security audits, and more.

## Installation

### NPM
```bash
npx kubectl-mcp-server
```

### Python
```bash
pip install kubectl-mcp-server
```

## Features

### Cluster Operations
- View cluster information
- Node management
- Namespace operations
- Resource quotas
- Context switching

### Workload Management
- Deploy applications
- Manage pods, deployments, services
- StatefulSets and DaemonSets
- Jobs and CronJobs
- Scaling operations

### Debugging Tools
- Pod log streaming
- Execute commands in containers
- Port forwarding
- Resource inspection
- Event monitoring
- Troubleshooting assistance

### Cost Optimization
- Resource usage analysis
- Right-sizing recommendations
- Unused resource detection
- Cost allocation tracking
- Efficiency metrics

### Security Audits
- RBAC configuration review
- Security context analysis
- Network policy validation
- Secret and ConfigMap inspection
- Vulnerability scanning integration

### Helm Integration
- Chart installation
- Release management
- Value customization
- Rollback operations
- Repository management

## Natural Language Commands

**Examples:**
- "Show me all pods in production namespace"
- "Scale the frontend deployment to 5 replicas"
- "Check why the database pod is failing"
- "Install nginx using Helm"
- "Audit security settings for api-server"
- "Find pods using too much memory"

## Use Cases

- Kubernetes cluster administration
- Application deployment automation
- Troubleshooting and debugging
- Cost optimization
- Security compliance
- Disaster recovery
- CI/CD integration
- Infrastructure monitoring

## Advanced Features

### Resource Management
- CPU and memory requests/limits
- Storage provisioning
- Network configuration
- Auto-scaling setup

### Configuration
- ConfigMap and Secret management
- Environment variable handling
- Volume mounting
- Service discovery

### Monitoring
- Metrics collection
- Health checks
- Liveness and readiness probes
- Performance analysis

## Multi-Cluster Support

- Manage multiple clusters
- Context switching
- Cluster comparison
- Multi-cloud support
- Federated operations

## Technical Implementation

Built with both Node.js and Python implementations, using official Kubernetes client libraries. Supports all kubectl functionality through natural language interface.

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Requires kubeconfig file or cluster credentials.

## Security

- Respects Kubernetes RBAC
- Secure credential handling
- Audit logging
- No privilege escalation
- Encrypted communications