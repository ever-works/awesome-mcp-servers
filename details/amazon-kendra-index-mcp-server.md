# Amazon Kendra Index MCP Server

## Overview
An AWS Labs Model Context Protocol (MCP) server that connects to Amazon Kendra indexes so MCP-enabled assistants can use Kendra as an additional context source for retrieval-augmented generation (RAG) and enterprise search.

- **Category:** Search & Discovery MCP Servers  
- **Vendor / Brand:** Amazon Web Services  
- **Primary use cases:**
  - Augment conversational and coding assistants with enterprise search results from Amazon Kendra indices
  - Query existing Kendra indexes for documentation, knowledge base, and RAG workflows

## Features

### Core Capabilities
- Connects MCP-enabled chatbots to Amazon Kendra indexes as RAG data sources.
- Enhances responses from coding and AI assistants (e.g., Cline, Cursor, Windsurf, Amazon Q Developer) by injecting Kendra search results into context.
- Supports querying either a default Kendra index or a specific index referenced in the user prompt.
- Can list available Amazon Kendra indexes in your AWS account to help select an appropriate index at runtime.

### Tools

#### 1. KendraQueryTool
- **Function:** Uses a natural-language query to search an Amazon Kendra index and retrieve additional context for the assistant’s response.
- **Behavior:**
  - Queries a default index, or
  - Queries a specific index if the user names it in the prompt.
- **Required parameters:**
  - `query` (str) – The user’s search query.
- **Optional parameters:**
  - `indexId` (str) – ID of the Kendra index to query.
  - `region` (str) – AWS region of the target Kendra index.
- **Example usage prompts:**
  - “Can you help me understand how to implement a progress event in the CreateHandler using Java? Use the KendraQueryTool to gain additional context.”
  - “Can you use the test-kendra-index to help answer the following questions…?”

#### 2. KendraListIndexesTool
- **Function:** Lists Amazon Kendra indexes in the AWS account.
- **Behavior:**
  - By default, lists indices in regions defined via environment variables in the MCP configuration.
  - Region can be overridden in the user prompt.
- **Optional parameters:**
  - `region` (str) – AWS region whose Kendra indexes should be listed.
- **Example usage prompt:**
  - “Can you list the Kendra Indexes in my account in the us-west-2 region?”

## Requirements

### Pre-Requisites
1. An AWS account.
2. An Amazon Kendra index containing the documentation or data you want to use for RAG.
3. `uv` installed (from Astral) for environment and dependency management.
4. Python 3.10 installed (e.g., via `uv python install 3.10`).

### IAM & AWS Configuration
1. Create or use an IAM user in your AWS account.
2. Attach a policy with, at minimum:
   - `kendra:Query`
   - `kendra:ListIndices`
   - (Alternatively, the managed policy `AmazonKendraFullAccess`, following least-privilege principles.)
3. Configure AWS credentials (access key ID and secret access key) in the environment using `aws configure`.

### Editor / Client Integration
- Installable as an MCP server in compatible clients such as Cursor and VS Code via provided install links/config.

## Pricing
No specific pricing information is provided for the MCP server itself. Usage will typically incur standard AWS charges for:
- Amazon Kendra (index storage, queries, and related operations), and
- Any other underlying AWS resources used by your account.

Consult AWS pricing pages for Amazon Kendra and related services for detailed cost information.