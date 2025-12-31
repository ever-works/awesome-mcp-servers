# OpenAI MCP Server

## Overview
The **OpenAI (ChatGPT) MCP Server** from Pipedream exposes OpenAI’s models (such as ChatGPT, DALL·E, and Whisper) over the Model Context Protocol (MCP). It provides a single MCP endpoint that clients can add to enable chat, text generation, summarization, translation, and assistants tooling workflows.

- **Category:** AI Integration – MCP Servers  
- **Provider / Brand:** OpenAI (via Pipedream MCP)  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Use cases:** Chat, completions, assistants, file handling, vector stores, summarization, translation, and related AI tasks against OpenAI APIs.

## Features

### MCP Server & Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable by any compatible client.
- Authentication handled when adding the server to your MCP-compatible application.
- Guides available for configuring with specific clients (e.g., ChatGPT) via Pipedream’s configuration page.
- Centralized configuration and account management via Pipedream sign-in.

### OpenAI Model Access (High-Level)
- Access to OpenAI chat and completion models (e.g., ChatGPT / GPT family) for conversational and text generation tasks.
- Access to Whisper-related capabilities for speech / text translation workflows.
- Integration with OpenAI Assistants features (threads, runs, tools, vector stores).

### Available Tools (Actions)
The server exposes **41 actions** as tools. The content lists the following explicitly:

1. **Upload File**  
   - Upload files for use across various OpenAI endpoints and features.  
   - Supports individual files up to **512 MB**.  
   - Useful for assistants, vector stores, or other file-based operations.

2. **Translate Text (Whisper)**  
   - Translate text from one language to another using OpenAI’s **Chat API** (leveraging Whisper-related capabilities where appropriate).

3. **Summarize Text**  
   - Generate text summaries using the **Chat API**.  
   - Suitable for condensing long documents, messages, or content blocks.

4. **Submit Tool Outputs to Run (Assistants)**  
   - Submit tool outputs back to an OpenAI **Assistants** run that is waiting for tool results.  
   - Supports building complex, tool-augmented assistants workflows.

5. **Create Completion (Send Prompt)**  
   - Create text completions using the older `/completions` API.  
   - Intended for legacy use; OpenAI recommends using the newer Chat-based APIs (e.g., `gpt-3.5-turbo`) for better performance and cost.

6. **Retrieve Vector Store**  
   - Retrieve metadata and details of a specific **vector store** used with OpenAI Assistants.

7. **Retrieve Vector Store File**  
   - Retrieve information about a specific **file** within a vector store.

8. **Retrieve Run (Assistants)**  
   - Retrieve a specific **run** within an assistant thread.  
   - Useful for checking status, outputs, or debugging assistant workflows.

9. **Retrieve Run Step (Assistants)**  
   - Retrieve details of a single **run step** in an assistant thread.  
   - Enables fine-grained inspection of the sequence of actions taken during a run.

> Note: In total there are **41 actions** exposed as MCP tools. Only the above subset is listed in the provided content; additional tools cover further OpenAI API capabilities but are not detailed in the excerpt.

## Configuration & Usage
- **Connect account:** Sign in via Pipedream to connect your OpenAI account and manage credentials.
- **Copy MCP URL:** Use the static MCP URL `https://mcp.pipedream.net/v2` in any MCP-compatible client.
- **Client setup:** Select your chat client (e.g., ChatGPT) and follow the Pipedream guide to add the MCP server and authenticate.
- **Tool access:** Once configured, all exposed actions (41 tools) are available for invocation from the client.

## Pricing
No pricing information is provided in the available content. The MCP server likely requires:
- An OpenAI account with usage-based billing for API calls, and
- (Potentially) a Pipedream account subject to Pipedream’s own pricing, which is not specified in the excerpt.

For exact pricing, refer to:
- OpenAI API pricing: https://platform.openai.com/pricing  
- Pipedream pricing (if applicable) on their official site.