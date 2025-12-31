# Langflow DOC QA Server

## Overview
Langflow DOC QA Server is a TypeScript-based Model Context Protocol (MCP) server that exposes a document question-answering (Q&A) capability backed by a Langflow “Document Q&A” flow. It provides a simple interface for querying documents via a Langflow backend.

- **Type**: MCP server
- **Tech stack**: TypeScript
- **Backend**: Langflow Document Q&A flow
- **Use case**: Document question answering / document querying

## Features
- **MCP-compliant server**  
  - Implements the Model Context Protocol for integration with MCP-compatible clients and tools.

- **Document Q&A via Langflow**  
  - Connects to a Langflow “Document Q&A” template/flow.  
  - Uses typical Langflow components such as ChatInput, File Upload, LLM, etc., as configured in your flow.

- **Simple document query interface**  
  - Provides a straightforward interface to send questions and document context to the Langflow backend.  
  - Designed as a minimal, illustrative example of how to wire an MCP server to a Langflow-based Q&A pipeline.

- **Configurable backend endpoint**  
  - Uses a configurable `API_ENDPOINT` (the Langflow flow’s API URL).  
  - Compatible with Langflow’s REST API, using the `run` endpoint for a specific flow ID (e.g. `http://127.0.0.1:7860/api/v1/run/<flow-id>?stream=false`).

- **Integration with Langflow flows**  
  - Works with Langflow flows created from the "Document Q&A" template.  
  - Supports custom configuration of components within the Langflow flow (LLM choice, file handling, prompt logic, etc.) as defined on the Langflow side.

- **Demonstration of core MCP concepts**  
  - Intended as a reference implementation or starter project for building MCP servers that connect to Langflow or similar backends.

## Setup Requirements (from content)
- A Langflow instance where you can
  - Create a flow from the **“Document Q&A”** template.  
  - Configure components such as **ChatInput**, **File Upload**, **LLM**, etc.  
  - Obtain the flow’s **API endpoint** via the **API** button in Langflow and copy the `run/<flow-id>` URL.
- Configure the MCP server with this API endpoint as `API_ENDPOINT`.

## Category
- Content extraction & summarization MCP servers

## Tags
- document-query  
- question-answering  
- ai-integration

## Pricing
No pricing information is provided in the available content; the project appears to be an open-source MCP server implementation hosted on GitHub.