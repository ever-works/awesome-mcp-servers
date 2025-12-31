# container-use

**Brand:** dagger  
**Category:** Code Execution Automation MCP Servers  
**Source:** https://github.com/dagger/container-use  
**Website:** https://container-use.com

## Overview

container-use is an MCP-compatible server from Dagger that provisions and manages containerized development environments for coding agents. It allows multiple agents to work safely and independently in isolated, fresh containers while reusing persistent volumes and cached images for efficient, repeatable code execution workflows.

## Features

- **MCP-compatible server**
  - Implements the Model Context Protocol (MCP) to integrate with MCP-aware coding agents and tools.

- **Containerized environments for coding agents**
  - Spins up development environments as containers rather than running code directly on the host.
  - Designed specifically for AI / coding agents and automated workflows.

- **Multi-agent isolation**
  - Enables multiple agents to run concurrently in separate containers.
  - Each agent operates safely and independently, reducing risk of interference between workflows.

- **Fresh containers per workflow**
  - Environments are instantiated as new containers to ensure a clean, reproducible state for each run or task.

- **Persistent volumes**
  - Supports persistent storage volumes so data, dependencies, or intermediate results can survive across container instances when desired.

- **Cached container images**
  - Reuses cached images to speed up environment provisioning and reduce startup overhead.

- **Preferred stack support**
  - Designed to be used with the user’s preferred language and tooling stack inside the containers (e.g., language runtimes, build tools, frameworks), configured through container images.

- **Repository & configuration structure**
  - `.container-use` and `environment` directories to describe environment behavior and configuration.
  - `examples` directory with sample setups and usage patterns.
  - `mcpserver` and `cmd/container-use` components for server and CLI/binary implementation.
  - `rules`, `repository`, and `scripts` directories for rule sets, repository integration, and automation scripts.

- **Open source licensing**
  - Released under the Apache-2.0 license.

## Use Cases

- Running AI coding agents in safe, disposable environments.
- Parallel execution of multiple autonomous agents with isolation.
- CI-like, reproducible dev environments for automated code modifications.
- Long-lived workspaces with persistent volumes combined with clean container re-creation.

## Pricing

No pricing information is provided in the available content. The project is open source under the Apache-2.0 license; any commercial or hosted offerings (if they exist) are not described in the provided material.
