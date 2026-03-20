## Overview

Salesforce DX MCP Server is the official Model Context Protocol implementation from Salesforce, enabling AI assistants to interact with Salesforce orgs, manage resources, and automate CRM operations through natural language commands.

## Features

### Org Management
- Connect to Salesforce orgs
- Switch between orgs and sandboxes
- Query org metadata
- Manage user permissions
- Monitor org limits

### Data Operations
- SOQL query execution
- SOSL search operations
- Record CRUD operations
- Bulk data management
- Data import and export

### Metadata Management
- Deploy and retrieve metadata
- Create and manage custom objects
- Configure fields and relationships
- Manage Apex classes and triggers
- Lightning component development

### Development Tools
- Apex code execution
- Test class running
- Code coverage analysis
- Debug log analysis
- Package development

## Salesforce Resources

### Standard Objects
- Accounts, Contacts, Leads
- Opportunities, Cases
- Tasks and Events
- Custom objects

### Automation
- Flows and Process Builder
- Workflow rules
- Approval processes
- Scheduled jobs

### Security
- Profile and permission set management
- Sharing rules
- Field-level security
- Object permissions

## Use Cases

- Automated CRM data management
- Salesforce org configuration
- Development workflow automation
- Data migration and integration
- Custom app development
- Report and dashboard creation
- User and permission management
- Testing and deployment automation

## Enterprise Features

- Multi-org support
- Sandbox management
- CI/CD integration
- Change set deployment
- Package management
- Scratch org creation

## Technical Implementation

Built by Salesforce using the official Salesforce CLI and APIs. Provides secure authentication through OAuth 2.0 and supports both production and sandbox orgs.

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Requires Salesforce org credentials and appropriate user permissions.

## Security & Compliance

Respects Salesforce security model including:
- Object-level security
- Field-level security
- Record-level security (sharing rules)
- API limits and governance
- Audit trail logging