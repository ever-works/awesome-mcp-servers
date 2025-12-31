## Parallel Task MCP Server

### Overview
The Parallel Task MCP Server is an MCP-compatible server that lets AI assistants and IDE agents run async web research and data enrichment workflows using Parallel’s Task API infrastructure. It exposes tools for creating deep research tasks, running task groups in parallel, and fetching results in an LLM-friendly format.

### Features
- **Deep research task creation**
  - Tool: **Create Deep Research Task**
  - Initiates a deep research workflow via Parallel’s Task API
  - Generates comprehensive research reports based on a given query or input
  - Returns metadata/details needed to track task progress

- **Parallel task group execution**
  - Tool: **Create Task Group**
  - Starts a Task Group to enrich or research multiple items in parallel
  - Designed for batch-style enrichment and web intelligence over datasets

- **Result retrieval**
  - Tool: **Get Result**
  - Retrieves results for both:
    - Deep research tasks
    - Task groups
  - Returns data in an LLM-friendly, structured format suitable for analysis and follow-up

- **Async architecture for agents**
  - Tasks are executed asynchronously so agents are not blocked while research runs
  - Agents can continue the conversation or perform other actions while tasks are in progress
  - Supports spawning many tasks in parallel without waiting for each to complete serially

- **Progress viewing and analysis support**
  - Returned task details include a link to view progress of ongoing work
  - Intended workflow:
    1. **Choose a data source** to start from (see “Enrichment Data Sources and Destinations” in the docs)
    2. **Initiate tasks** (deep research or task groups) using the MCP tools
    3. **Analyze results** once tasks complete, using the LLM to interpret and summarize the outputs

- **LLM client integration pattern**
  - Due to current MCP / LLM client limitations, the result retrieval must be initiated in a **separate turn** after tasks finish
  - The expected pattern is:
    - First turn: create deep research task or task group
    - Later turn: call **Get Result** once results are ready

- **Built on Parallel Task API infrastructure**
  - Uses the same backend as Parallel’s Task API (including deep research and group APIs)
  - Aims to provide consistent research quality across different price points while reducing custom integration work for MCP-compatible clients

### Use Workflow (Recommended)
1. **Choose data source** for enrichment or research (e.g., a dataset or list of items).
2. **Initiate tasks** via:
   - Create Deep Research Task (for a single comprehensive research report), or
   - Create Task Group (for multiple items in parallel).
3. **Retrieve and analyze results** by:
   - Calling Get Result in a later turn after completion,
   - Using the LLM/agent to interpret, synthesize, and act on the returned data.

### Pricing
The provided content does not include pricing details specific to the Parallel Task MCP Server. Refer to Parallel’s main Pricing page for current information.