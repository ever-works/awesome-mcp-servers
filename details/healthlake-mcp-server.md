# HealthLake MCP Server

**Category:** Data Access & Integration – MCP Servers  
**Vendor:** AWS  
**Tags:** healthcare, FHIR, AWS

An MCP server that integrates with AWS HealthLake datastores to perform FHIR interactions, enabling healthcare data workflows over the Model Context Protocol (MCP).

---

## Overview

HealthLake MCP Server is part of the AWS MCP Servers suite. It exposes AWS HealthLake capabilities through MCP so that AI assistants and tools can work directly with FHIR data stored in HealthLake. This allows healthcare and life sciences workflows to run over standardized FHIR APIs using MCP-compatible clients.

---

## Features

- **FHIR interaction support**  
  - Performs FHIR operations (e.g., read/search/update) against AWS HealthLake datastores.  
  - Uses standardized FHIR resources to structure healthcare data.

- **AWS HealthLake datastore integration**  
  - Connects MCP clients to one or more AWS HealthLake datastores.  
  - Enables workflows that read and manage clinical and other healthcare data in a compliant store.

- **MCP-compatible server**  
  - Implements the Model Context Protocol so it can be used by MCP-aware tools and assistants (e.g., compatible IDEs, agents, or chat-based tools).  
  - Fits into the broader AWS MCP Servers ecosystem alongside other domain-specific servers.

- **Healthcare & life sciences workflows**  
  - Designed specifically for healthcare and life sciences use cases that rely on FHIR data models.  
  - Supports building data access, analytics, and operational workflows over clinical data.

- **AWS-native environment**  
  - Built to work with AWS services and security practices (e.g., IAM, AWS regions) via HealthLake.  
  - Allows consolidating healthcare data workflows within AWS infrastructure.

> Note: The source content is high-level; detailed operation lists, configuration options, or example tools are not explicitly described beyond the general FHIR/HealthLake/MCP integration.

---

## Pricing

The provided content does not describe any specific pricing or plans for HealthLake MCP Server. It is distributed as part of the open-source `awslabs/mcp` GitHub project (Apache-2.0 license indicated for the repository); AWS HealthLake service usage is billed separately under its own AWS pricing.

---

## Source

- GitHub (README): https://github.com/awslabs/mcp  
- Raw README URL: https://raw.githubusercontent.com/awslabs/mcp/main/README.md
