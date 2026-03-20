## Overview

The official Terraform MCP Server from HashiCorp provides comprehensive integration with the Terraform ecosystem, enabling advanced automation and interaction capabilities for Infrastructure as Code (IaC) development. It bridges AI assistants with Terraform's powerful infrastructure management tools.

## Features

- **Terraform Registry Integration**: Direct access to Terraform Registry APIs for module and provider discovery
- **HCP Terraform Support**: Full integration with HCP Terraform (formerly Terraform Cloud) and Terraform Enterprise
- **Workspace Operations**: Manage workspaces, runs, and state files through natural language
- **Multiple Transport Methods**: Supports both Stdio and StreamableHTTP transports for flexible deployment
- **Module Discovery**: Search and explore Terraform modules from the public registry
- **Provider Management**: Query and manage Terraform providers and their versions
- **State Management**: Safe interaction with Terraform state files
- **Run Automation**: Trigger and monitor Terraform plan and apply operations

## Use Cases

- Infrastructure as Code development assistance
- Automated infrastructure provisioning
- Module and provider discovery
- Workspace management and organization
- Documentation generation for Terraform configurations
- Cost estimation and optimization
- Compliance checking and policy validation

## Technical Implementation

Built and maintained by HashiCorp, ensuring compatibility with official Terraform tools and APIs. The server implements the Model Context Protocol standard while providing specialized tools for Terraform workflows.

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Supports authentication with HCP Terraform and Terraform Enterprise through standard API tokens.

## Enterprise Features

For HCP Terraform and Terraform Enterprise users, additional features include team management, policy as code integration, cost estimation, and audit logging.