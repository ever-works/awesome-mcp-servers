# Terraform MCP Server

## Overview
The Terraform MCP Server is a Model Context Protocol (MCP) server designed to integrate AI models with Terraform workflows. It provides real-time access to Terraform provider documentation, modules, and policies from the Terraform Registry, as well as HCP Terraform and Terraform Enterprise workspaces. This enables AI-assisted authoring, validation, and management of Terraform infrastructure-as-code using current, authoritative data.

> Note: The Terraform MCP Server is currently in beta and is not recommended for production environments.

## Features

### MCP-based AI Integration
- Implements the open Model Context Protocol (MCP) for secure connection between AI models and external Terraform data sources.
- Allows AI models to access information beyond their training data for more current and accurate Terraform responses.
- Enables AI-assisted generation of Terraform configuration that is grounded in live provider and registry data.

### Real-time Terraform Registry Access
- **Real-time accuracy**: Uses current provider documentation instead of relying on potentially outdated training data.
- **Terraform Registry integration**:
  - Direct integration with public Terraform Registry APIs.
  - Access to providers, modules, and policies.
- AI models can:
  - Search and retrieve current provider documentation.
  - Access module details, including inputs, outputs, and example usage.
  - Find Sentinel policies related to governance and compliance.

### HCP Terraform & Terraform Enterprise Integration
- **Workspace and organization integration** with HCP Terraform and Terraform Enterprise (TFE):
  - Organization and project listing.
  - Workspace listing and inspection.
  - Access to private registries (via HCP Terraform / TFE).
- **Workspace operations**:
  - Create, update, and delete workspaces.
  - Manage workspace variables.
  - Manage workspace tags.
  - Manage workspace runs (run management capabilities).
- **Variable and tag management tools**:
  - Create, read, update, and delete workspace variables.
  - Create, read, update, and delete workspace tags.
  - Manage variable sets (create, read, update, delete).

### AI-Driven Terraform Authoring and Management
- Enhances AI models with specialized tools for Terraform-specific tasks.
- Ensures AI-generated Terraform configurations:
  - Use accurate provider arguments and resource types.
  - Reference the latest module versions and examples.
  - Can be aligned with Sentinel policies for compliance guidance.
- Supports infrastructure-as-code workflows where AI can:
  - Propose or refine Terraform configuration.
  - Suggest modules and providers that match requirements.
  - Surface relevant policies and best practices.

### Deployment Architecture Components
- **AI model**: The large language model that generates and refines Terraform-related content based on user prompts.
- **MCP host**: The AI application or environment that runs the model and manages MCP client interactions (e.g., tools like Claude Desktop).
- **MCP client**: The component that discovers Terraform MCP server tools and translates model prompts into executable actions against the MCP server.
- **MCP server (Terraform MCP Server)**: The backend service that:
  - Connects to Terraform Registry APIs.
  - Connects to HCP Terraform / Terraform Enterprise.
  - Executes requests for docs, modules, policies, and workspace operations on behalf of the AI model.

## Use Cases
- AI-assisted writing and refactoring of Terraform configuration using live provider documentation.
- Discovering and integrating appropriate Terraform modules from the Registry with accurate input/output usage.
- Enforcing or checking against Sentinel policies by surfacing relevant policies during configuration authoring.
- Managing HCP Terraform / TFE workspaces (creation, updates, variables, tags, runs) through AI-driven workflows.

## Pricing
The provided content does not include any pricing information or plan details for the Terraform MCP Server.