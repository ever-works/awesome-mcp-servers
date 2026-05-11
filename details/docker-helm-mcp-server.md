## Overview

The Docker Helm MCP Server provides a bridge between AI assistants and the Helm package manager for Kubernetes. It enables natural language interactions with Helm repositories, chart management, and Kubernetes application deployments.

## Features

- **Helm Repository Management**: Browse and search Helm repositories
- **Chart Operations**: Install, upgrade, and manage Helm charts
- **Release Management**: Track and manage Helm releases across clusters
- **OCI Registry Support**: Work with Helm charts stored in OCI registries
- **Multi-version Support**: Handle multiple chart versions and tags
- **SSE Mode**: Server-sent events transport for real-time updates
- Authentication for private repositories

## Installation

Can be deployed as a Docker container:

```bash
docker run -d --name mcp-helm -p 8012:8012 ghcr.io/zekker6/mcp-helm:v1.3.0 -mode=sse
```

## Use Cases

- Automate Helm chart deployments through AI conversations
- Search and discover available Helm charts using natural language
- Manage Kubernetes applications with AI-assisted workflows

## Pricing

Free and open-source.