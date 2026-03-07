## Overview

Multiple MCP (Model Context Protocol) server implementations enable AI assistants (Claude, ChatGPT, etc.) to interact with the Twilio SendGrid v3 API for email automation, template management, and delivery tracking.

## Available Implementations

### Garoth/sendgrid-mcp
Allows AI Agents to interact with the Twilio SendGrid v3 API:
- **Contact Management**: List, add, delete contacts
- **Contact Lists**: Manage contact list operations
- **Email Templates**: Template management
- **Single Email Sending**: Send individual emails
- **Statistics**: Email statistics and validation
- **Verified Senders**: Sender email addresses must be verified with SendGrid before use

### recepyavuz0/sendgrid-mcp-server
SendGrid API Integration For LLMs with features:
- Single and batch email sending
- Template-based emails
- Scheduled emails
- Email statistics and reports

### @cong/sendgrid-mcp (JSR/Deno)
Built with Deno and TypeScript:
- Full MCP server implementation
- Input validation using Zod schemas
- HTML sanitization for security
- Complete test suite

### Official Twilio Tutorial
Model Context Protocol (MCP) is an open standard developed by Anthropic that lets you connect AI models to external services through MCP servers, allowing models to take actions such as sending emails, updating databases, or working with APIs.

### Composio MCP Integration
Choose your AI platform: Cursor, Claude Desktop, Windsurf, or use HTTP endpoint for custom integrations.

## Use Cases

- AI-powered email campaigns
- Automated transactional emails
- Template-based communication
- Email delivery tracking
- Contact list management

## Integration

Works with Claude Desktop, Cursor, and other MCP-compatible AI assistants.