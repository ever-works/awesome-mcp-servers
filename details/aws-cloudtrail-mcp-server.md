# AWS CloudTrail MCP Server

**Category:** Security & Attestation MCP Servers  
**Brand:** Amazon Web Services (AWS)

## Overview
AWS CloudTrail MCP Server is a Model Context Protocol (MCP) server that exposes AWS CloudTrail logs to MCP-compatible clients. It enables analysis of API activity across AWS services, including users and resources involved in those actions, to support automated security monitoring and operational insights.

## Features
- **CloudTrail log surfacing**  
  - Connects to AWS CloudTrail and makes log data available through MCP.  
  - Surfaces events for AWS API calls across supported AWS services.

- **API activity analysis**  
  - Provides detailed records of API calls, including which services were accessed and how.  
  - Enables inspection of request and response details, as captured by CloudTrail logs.

- **User and identity tracking**  
  - Identifies which users, roles, or principals invoked specific API calls (as recorded by CloudTrail).  
  - Supports auditing and investigation of user activity for security and compliance use cases.

- **Resource-level visibility**  
  - Associates API calls with affected AWS resources where available in CloudTrail events.  
  - Helps trace configuration changes and access patterns on key resources.

- **Automated security insights via MCP**  
  - Allows MCP-aware tools and agents to query and reason over CloudTrail logs.  
  - Can be used to detect suspicious activity, policy violations, or anomalies based on log data.

- **Operations and compliance insights**  
  - Supports operational troubleshooting and change tracking by exposing historical API actions.  
  - Can be integrated into workflows for governance and compliance reporting within MCP-based systems.

## Integrations
- **Model Context Protocol (MCP)**  
  - Exposes CloudTrail data as an MCP server for consumption by MCP clients.
- **AWS CloudTrail**  
  - Relies on existing AWS CloudTrail logging configuration in your AWS account.

## Pricing
Pricing information is not provided in the available content.