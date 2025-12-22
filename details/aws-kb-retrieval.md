# AWS KB Retrieval

**Description:**  
AWS KB Retrieval is an MCP (Model Context Protocol) server that retrieves content from AWS Knowledge Bases using the Amazon Bedrock Agent Runtime, allowing LLMs to query and use AWS-hosted knowledge resources in their responses.

**Category:** mcp-server-directories-lists

---

## Features
- **MCP server implementation** for integrating external tools and data sources into LLM workflows.
- **Retrieval from AWS Knowledge Bases**, enabling access to centralized, AWS-hosted knowledge content.
- **Uses Amazon Bedrock Agent Runtime** to handle requests and responses to AWS Knowledge Bases.
- **LLM-ready interface**, designed so large language models can query knowledge resources programmatically through MCP.
- **Supports retrieval-augmented workflows**, where LLMs fetch relevant knowledge-base content at query time.

---

## Use Cases
- Powering LLM assistants with up-to-date information stored in AWS Knowledge Bases.
- Building internal tools or chatbots that answer questions from organizational knowledge hosted in AWS.
- Adding AWS Knowledge Base retrieval as a tool within MCP-compatible LLM environments.

---

## Integrations
- **AWS Knowledge Bases** (as the primary knowledge source).
- **Amazon Bedrock Agent Runtime** (for executing retrieval operations).
- **MCP-compatible LLM clients/tools** that can call MCP servers.

---

## Pricing
Pricing information is not provided in the available content. Refer to the project’s repository for details and note that usage of AWS services (e.g., Bedrock, Knowledge Bases) may incur AWS charges according to your AWS account and configuration.

---

## Links
- **Source / Repository:** https://github.com/madhukarkumar/anthropic-mcp-servers/blob/main/src/aws-kb-retrieval-server
- **Slug:** `aws-kb-retrieval`