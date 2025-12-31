# Cortex MCP Server

**Category:** Cloud & DevOps – MCP Servers  
**Vendor:** Cortex  
**Website:** https://mcp.cortex.io/mcp

## Overview
Cortex MCP Server connects the Cortex internal developer portal (IDP) to AI coding assistants and IDEs via the Model Context Protocol (MCP). It exposes real-time engineering context—such as services, teams, standards, and initiatives—so developers can query their organization’s software catalog and operational state in natural language directly from their IDE, instead of switching to the Cortex UI.

## Features

### IDE and AI Assistant Integration
- Integrates Cortex with IDE-based AI coding assistants using MCP.
- Allows developers to ask natural language questions (e.g., about production readiness, on-call context, or recent changes) and receive answers grounded in Cortex data.
- Reduces context switching between the IDE and the internal developer portal.

### Unified Engineering Context
- Provides a single MCP endpoint that aggregates engineering context otherwise spread across tools (e.g., GitHub, PagerDuty, Jira) and Cortex’s own catalog.
- Supplies more complete, organization-wide context than standalone MCP integrations to improve answer quality from AI assistants.

### Entities (Service & Resource Catalog)
- Exposes the full Cortex catalog via MCP, including:
  - Microservices
  - Libraries
  - Domains
  - Teams
  - Infrastructure resources
  - Other entity types managed in Cortex
- Enables queries about ownership, relationships, and other attributes for entities in the catalog.

### Scorecards (Standards & Readiness)
- Surfaces scorecard data through MCP so AI assistants can:
  - Understand how the organization measures engineering standards and best practices.
  - Check compliance, readiness, and other scorecard-based metrics for entities.
- Supports use cases like assessing production readiness or verifying adherence to security and reliability standards.

### Initiatives (Goals & Deadlines)
- Exposes initiative data representing organization-wide goals and projects.
- Provides context on:
  - Defined objectives and targets
  - Deadlines and timelines
  - Which entities or teams are in scope
- Helps AI assistants answer questions about ongoing efforts, migrations, and accountable owners.

### Operational and On-Call Context (via Catalog + Scorecards + Initiatives)
- Supports scenarios such as:
  - On-call engineers requesting recent deploy history, documentation, runbooks, and dependencies for a service.
  - Platform or SRE teams checking status of migrations, production readiness, or security/compliance work against deadlines.
- Uses Cortex’s combined entity, scorecard, and initiative data to provide richer, situational responses.

### Setup and Availability
- Available for all existing Cortex customers.
- Designed to be configured in minutes using the official documentation at https://docs.cortex.io/mcp.
- Uses API key–based authentication (as noted in the item metadata) to connect to Cortex.

### Extensibility and Ongoing Improvements
- Built to support increasingly advanced AI workflows, evolving from answering questions toward enabling AI agents to take action based on Cortex context.
- Cortex actively iterates on the MCP server based on customer feedback to broaden supported use cases.

## Pricing
- The content indicates that the Cortex MCP Server is “available for all customers” but does not list specific pricing tiers or plans.
- Pricing is therefore implied to be included as part of a Cortex subscription, with no separate, public MCP-specific pricing details provided in the source content.