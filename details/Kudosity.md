# What is MCP?

Model Context Protocol (MCP) is an open standard that allows AI applications to securely access external data sources and tools. The Kudosity MCP server provides AI agents with:

- Direct API access to Kudosity functionality — send messages, update contact lists, etc.
- Documentation search — have your AI intelligently search API specs and tutorials to provide on-point answers.
- Real-time data from your Kudosity account — query and execute live operations directly from chat.
- Code generation for Kudosity integrations
- Live API execution — beyond static examples, run real requests
- Always up-to-date — powered by Swagger API source definitions

# MCP Server Capabilities
The Kudosity MCP server offers comprehensive tools for API discovery, documentation, code generation, and live execution:

## 🔍 API Discovery & Exploration
- **list-specs** — discover available messaging APIs (SMS, RCS, WhatsApp, etc.)
- **list-endpoints** — list all API paths and methods for a service
- **get-endpoint** — inspect supported methods and parameters for any path
-0 **search-specs** — search across specs for keywords or patterns

## 📋 API Schema & Documentation
- **get-request-body** — retrieve request body schema for any endpoint
- **get-response-schema** — view response schema for specific endpoints and status codes
- **list-security-schemes** — check authentication methods and requirements
- **search-documentation** — search API documentation content

## ⚡ Code Generation
- **get-code-snippet** — generate ready-to-run examples in curl, JavaScript, Python, etc.
- Provides proper authentication and parameters automatically

## 🚀 Live API Execution
- **execute-request** — run real API calls using HAR format
- Send test SMS messages
- Validate any Kudosity endpoint with live credentials
-Returns actual responses and errors

# Available APIs

**Documentation:**
https://developers.kudosity.com/docs/mcp

The MCP server provides access to these Kudosity APIs:

**1. Transmit Message API** — v2 messaging service supporting SMS, RCS, MMS, WhatsApp, and webhooks

**2. Transmit SMS API** — full-featured SMS with advanced contact lists, keywords, and reporting

# Kudosity MCP Server Setup 

**Kudosity remote MCP server:**
https://developers.kudosity.com/mcp

Configure your AI development tools to connect to this server.

## Authentication Configuration

For APIs that require authentication, you'll need to configure your API credentials. Depending on the endpoints, the methods differ:

- **api.transmitsms.com** (v1 endpoints) — Basic Authentication with Base64-encoded API Key and Secret

- **api.transmitmessage.com** (v2 endpoints) — API Key Authentication with your key in the `x-api-key` header

### For v1 endpoints (api.transmitsms.com) - Basic Authentication:

1. Get your credentials from Kudosity dashboard → Developers → API Settings
2. Combine as: `API_KEY:API_SECRET`
3. Base64 encode:
   1. Terminal: `echo -n "API_KEY:API_SECRET" | base64`
   2. Browser console: `btoa("API_KEY:API_SECRET")`
   3. Online tool: base64encode.org

### For v2 endpoints (api.transmitmessage.com) - API Key Authentication:

- Use your API Key directly in the `x-api-key` header (no Base64 encoding required).

Important: Restart your AI tool after saving the configuration file.

You can also install the Claude MCP integration for this project using Bash:

```
claude mcp add kudosity --scope project -- npx mcp-remote https://developers.kudosity.com/mcp
```

## Testing Your MCP Setup
Once configured, you can test your MCP server connection:

1. Restart your AI tool (Claude Desktop, Cursor, etc.)
2. Start a new chat with the AI assistant
3. Ask about Kudosity — try questions like:
   1. "What APIs does Kudosity offer?"
   2. "Show me an example of sending an SMS"
   3. "Create a curl command to send my first SMS through Kudosity"
   4. "How do I get started sending SMS with Kudosity"

If successful, the AI will respond with Kudosity API details and sample code pulled directly from your account and documentation.
