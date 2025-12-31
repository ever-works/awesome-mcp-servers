# Amazon EKS MCP Server

## Overview
Amazon EKS MCP Server is a Model Context Protocol (MCP) server deployment pattern for running Kubernetes-based MCP workloads on Amazon Elastic Kubernetes Service (EKS). It is used to manage Kubernetes clusters and deploy applications so MCP-aware agents (such as StrandsAgent) can interact with Kubernetes-hosted tools and services, typically in AI/agentic applications on AWS.

- **Category:** Cloud & DevOps – MCP Servers
- **Brand:** Amazon Web Services (AWS)
- **Source:** https://builder.aws.com/content/2zJTdRGobiH2RYtjHAW8hRqD0h6/agentic-genai-app-using-bedrock-mcp-servers-on-eks

## Features

### Kubernetes-based MCP hosting
- Runs MCP servers as stateless workloads on an Amazon EKS cluster.
- Uses Kubernetes primitives (Pods, Deployments, etc.) to manage MCP server lifecycle.
- Supports containerized MCP services, enabling standardized deployment and scaling.

### Integration with agent frameworks
- Designed to be called by MCP-aware agents (e.g., StrandsAgent).
- Provides context-aware logic and tools that agents can invoke as part of agentic workflows.
- Enables tool-calling patterns where the agent decides when to call MCP servers for additional data or actions.

### Application deployment on EKS
- Uses Amazon EKS as the control plane for deploying and managing MCP server applications.
- Enables separation of the frontend/agent runtime (e.g., Django + StrandsAgent) from the MCP tool layer running on Kubernetes.

### Scalability and resilience (implied from EKS usage)
- Leverages Kubernetes auto-scaling on EKS to scale MCP servers based on load.
- Benefits from EKS-managed cluster operations for high availability of MCP workloads.

### GenAI and Bedrock integration (solution context)
- Often used in solutions where:
  - Frontend (e.g., Django web app) sends user input.
  - An agent framework orchestrates steps.
  - Amazon Bedrock provides foundation model inference.
  - MCP servers on EKS supply specialized tools or context.
- Supports dynamic, conversational experiences by combining Bedrock models, agents, and MCP tools.

## Typical Architecture Role
- Acts as the **MCP tool layer** within an AI/agentic architecture on AWS:
  - Frontend → Agent (StrandsAgent) → Bedrock for LLM inference.
  - Agent invokes MCP servers on EKS when tools or external logic are required.

## Pricing
No specific pricing information for "Amazon EKS MCP Server" is provided in the source content. Costs are expected to derive from underlying AWS services (e.g., Amazon EKS cluster, compute, and related resources) according to standard AWS pricing, but exact details are not described in the referenced material.