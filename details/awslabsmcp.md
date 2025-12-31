---
title: "AWS MCP Servers"
slug: "awslabsmcp"
brand: "aws-labs"
featured: true
category: "cloud-devops-mcp-servers"
external_url: "https://github.com/awslabs/mcp"
source_url: "https://github.com/awslabs/mcp"
images:
  - "https://opengraph.githubassets.com/1/awslabs/mcp"
logo: "https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png"
tags:
  - aws
  - cloud
  - infrastructure
license: "Apache-2.0"
---

## Overview

**AWS MCP Servers** is an open‑source collection of official Model Context Protocol (MCP) servers from AWS. These servers provide programmatic integration between AI assistants and AWS services and resources, allowing tools that speak MCP to inspect and interact with AWS infrastructure.

## Features

- **Official AWS MCP server implementations**
  - Maintained under the `awslabs` organization with an Apache-2.0 license.
  - Designed to be used wherever MCP is supported (e.g., AI assistants and developer tools that implement the Model Context Protocol).

- **Integration with AWS services and resources**
  - Exposes AWS capabilities over MCP so assistants can interact with AWS infrastructure programmatically.
  - Targets a wide range of AWS services (exact service list is defined in the repository code and docs).

- **Extensible server collection**
  - Multiple servers under a single repository structure (`src`, `samples`, `testing` directories) enabling different AWS integrations.
  - Sample configurations and usage examples in the `samples` folder to help set up and customize integrations.

- **Developer-focused tooling and structure**
  - Development container configuration via `.devcontainer` for reproducible environments.
  - Pre-commit configuration, linting (`.ruff.toml`), and Python version pinning (`.python-version`).
  - GitHub workflows and automation under `.github`.

- **Documentation site**
  - Dedicated docs hosted at: https://awslabs.github.io/mcp/
  - Built with Docusaurus (present in the `docusaurus` directory).

- **Security and testing assets**
  - Security-related configuration (e.g., `.secrets.baseline`, `.vex` directory).
  - Structured testing setup in the `testing` directory.

## Use Cases

- Allow an MCP-compatible AI assistant to:
  - Inspect AWS resources programmatically.
  - Orchestrate workflows that involve AWS infrastructure.
  - Integrate AWS data and operations into conversational or tool-based agents.

## Pricing

- The project is open source under the Apache-2.0 license.
- No license fees for using the code; standard AWS service charges apply separately when calling AWS APIs from these servers.
