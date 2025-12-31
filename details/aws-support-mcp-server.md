## AWS Support MCP Server

**Category:** Cloud & DevOps MCP Servers  
**Brand:** AWS  
**Source:** <https://github.com/awslabs/mcp>

### Overview
AWS Support MCP Server is an open-source Model Context Protocol (MCP) server that allows you to create and manage AWS Support cases programmatically. It is part of the `awslabs/mcp` collection of AWS-focused MCP servers.

### Features
- **Programmatic AWS Support Case Management**  
  - Create AWS Support cases via MCP tools.  
  - Update and manage existing AWS Support cases.  
  - Retrieve details and status of AWS Support cases.

- **Model Context Protocol Integration**  
  - Exposes AWS Support functionality through the MCP standard so compatible AI assistants/clients can interact with AWS Support.  
  - Designed to be used alongside other MCP servers in the `awslabs/mcp` repo.

- **Open-Source Implementation**  
  - Source code available in the `awslabs/mcp` GitHub repository.  
  - Licensed under the Apache-2.0 license.  
  - Includes development assets such as devcontainer configuration, testing setup, and scripts (from the parent repo) to support local development and contribution.

- **Ecosystem & Samples (Repo-wide)**  
  - Sample configurations and examples under the `samples` directory to demonstrate MCP server usage.  
  - Documentation site generated with Docusaurus (`docusaurus` directory) for broader MCP server docs (including Support server usage when documented there).

### Technical Details
- **Repository:** `awslabs/mcp` (monorepo containing multiple AWS MCP servers, including AWS Support MCP Server).  
- **License:** Apache-2.0.  
- **Languages/Tooling:** Python-based tooling and configuration indicated by `.python-version`, `.ruff.toml`, `.pre-commit-config.yaml` (from the parent repo structure).

### Pricing
- **Open Source**: No license fee. The AWS Support MCP Server is provided under the Apache-2.0 open-source license.  
- **AWS Charges**: Any AWS Support or other AWS service usage is billed separately by AWS according to your AWS account and support plan.
