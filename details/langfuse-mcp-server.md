# Langfuse MCP Server

**Category:** Monitoring  
**Brand:** Langfuse  
**Slug:** `langfuse-mcp-server`

MCP server for Langfuse that integrates open‑source LLM observability features—traces, evaluations, prompt management, and metrics—into MCP-compatible applications.

---

## Description

Langfuse MCP Server connects MCP-enabled clients (such as ChatGPT with MCP support) to a Langfuse instance, enabling collection and management of observability data for LLM applications. It lets you log traces and attach user feedback from your MCP client into Langfuse’s open-source LLM engineering platform, supporting debugging, analysis, and continuous improvement of LLM-based workflows.

---

## Features

- **Open-source LLM observability integration**  
  - Connects MCP apps to Langfuse’s open-source LLM engineering platform.  
  - Supports centralized observability for LLM workflows.

- **Traces**  
  - Log traces for LLM requests and workflows from within MCP clients.  
  - Capture details of application runs to help debug and analyze behavior.

- **Evals (evaluations)**  
  - Integrates with Langfuse evaluation capabilities (mentioned at platform level) to assess LLM output quality over time.

- **Prompt management**  
  - Connects MCP traffic to Langfuse prompt management, enabling organization and iteration on prompts used in your LLM application.

- **Metrics and monitoring**  
  - Collects metrics about LLM usage and performance through Langfuse.  
  - Supports monitoring of application behavior for reliability and optimization.

- **Static MCP server URL**  
  - Single server endpoint for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Authentication handled when adding the server to your application.

- **Client integration support**  
  - Guidance for adding the MCP server to supported chat clients (e.g., ChatGPT / OpenAI).  
  - Links to a configuration page for broader MCP setup.

- **Available tools (actions)**  
  - **Log Trace**  
    - Log a new trace in Langfuse with associated details about the event or run.  
    - Implemented as an MCP action: `Log Trace`.
  - **Add Feedback**  
    - Attach user feedback to an existing trace in Langfuse.  
    - Enables tying qualitative feedback to specific traces for analysis.

- **MCP-native design**  
  - Designed to work across MCP-compatible clients using the same server URL.  
  - Operated and hosted via Pipedream’s MCP infrastructure.

---

## Integration Details

- **MCP server URL:** `https://mcp.pipedream.net/v2`  
- **Setup steps (high level):**  
  - Sign in with a Pipedream account to connect Langfuse.  
  - Copy the MCP server URL.  
  - Add the server to your MCP-compatible client (e.g., ChatGPT) following that client’s configuration guide.

---

## Tags

- `observability`  
- `llm`  
- `metrics`

---

## Pricing

Pricing information is not provided in the available content.