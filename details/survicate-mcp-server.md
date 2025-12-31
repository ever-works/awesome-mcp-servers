# Survicate MCP Server

**Description**  
Survicate MCP Server is an MCP server integration that connects AI tools and chat clients to Survicate’s survey, NPS, and feedback management platform, enabling automated access to surveys, responses, respondent data, and GDPR-related operations.

**Category:** Business & Commerce MCP Servers  
**Tags:** surveys, customer-feedback, NPS

---

## Features

### MCP Server & Connection
- Provides a static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
- Supports authentication when adding the server to compatible applications or chat clients.
- Allows connecting a Survicate account and selecting a specific client/workspace to manage.

### Survey Management & Retrieval
- **List Surveys**  
  Retrieve a list of all surveys from a Survicate workspace, enabling discovery and selection of available surveys.

- **Get Survey**  
  Fetch detailed information about a specific survey, including its configuration and content.

- **List Questions**  
  Retrieve a list of questions for a specific survey, allowing AI tools to understand the survey structure and content.

### Response & Respondent Data
- **List Responses**  
  Fetch a list of responses for a specific survey (by survey ID), useful for analysis, reporting, and follow-up actions.

- **Get Response**  
  Retrieve detailed information for a specific survey response, enabling granular analysis at the individual-response level.

- **List Respondent Responses**  
  Retrieve a list of all survey responses from a specific respondent (by respondent UUID), supporting longitudinal or user-centric analysis.

- **List Respondent Attributes**  
  Retrieve names and values of custom attributes associated with a specific respondent, including attributes passed via:
  - Survicate JavaScript API
  - Integrations
  - Embedded parameters in the survey link

### GDPR & Personal Data Operations
- **Get Personal Data Counters**  
  Retrieve counts of personal data records held, supporting GDPR and privacy-related reporting or audits.

- **Delete Personal Data**  
  Delete personal data associated with a specific email address, enabling GDPR-compliant data erasure workflows.

---

## Pricing
Pricing information is not provided in the available content.