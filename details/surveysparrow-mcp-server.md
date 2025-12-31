# SurveySparrow MCP Server

**Category:** Business & Commerce · MCP Servers  
**Tags:** survey, marketing, customer-feedback

SurveySparrow MCP Server is an integration endpoint that connects the SurveySparrow conversational survey platform to Model Context Protocol (MCP)-compatible AI clients. It enables AI agents to programmatically create, update, and distribute surveys, as well as manage contacts.

---

## Features

### MCP Integration
- Static MCP server URL: `https://mcp.pipedream.net/v2` usable for all clients.
- Authentication handled when adding the server to your MCP-compatible application.
- Works across multiple chat / AI clients via a common configuration flow.

### Survey Management
- **Create Survey**  
  - Programmatically create new surveys in SurveySparrow.
- **Update Survey**  
  - Modify existing surveys (e.g., questions, settings, or metadata as supported by SurveySparrow’s API).

### Survey Distribution & Engagement
- **Share Survey via Email**  
  - Send a saved email share template to a specified email address.  
  - Configure which saved template to use.  
  - Provide one or more recipient email addresses.
- **Share NPS Survey via SMS**  
  - Send a saved Net Promoter Score (NPS) survey template via SMS.  
  - Specify target mobile numbers for SMS delivery.

### Contact Management
- **Create Contact**  
  - Create new contacts in SurveySparrow for use in survey distribution and audience management.

### Tooling Summary
- Exposes 5 actions as MCP tools:
  1. Create Survey
  2. Update Survey
  3. Share Survey via Email
  4. Share NPS Survey via SMS
  5. Create Contact

---

## Pricing

Pricing information is not provided in the available content. Refer to the product or provider website for current pricing details.