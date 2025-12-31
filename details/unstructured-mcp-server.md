# Unstructured MCP Server

An MCP server for Unstructured that lets MCP agents run unstructured data ETL pipelines, preparing documents and other content for use with LLMs.

- **Name:** Unstructured MCP Server  
- **Category:** Data Access & Integration – MCP Servers  
- **Brand:** unstructured  
- **Source URL:** https://mcp.pipedream.com/app/unstructured  
- **Slug:** unstructured-mcp-server  
- **Tags:** unstructured-data, etl, llm-integration

---

## Description
The Unstructured MCP Server provides an MCP endpoint that allows agents and applications to run Unstructured-powered ETL pipelines over unstructured data (such as documents and other content) so that the results can be used effectively with LLMs.

The server is hosted via Pipedream Connect and is accessed through a static MCP URL that works across compatible MCP clients.

---

## Features
- **Unstructured data ETL for LLMs**  
  - Runs ETL pipelines specifically designed for unstructured content (e.g., documents, text blobs, and other raw content).  
  - Prepares and normalizes content for downstream LLM usage.

- **MCP server endpoint**  
  - Exposes functionality via the Model Context Protocol (MCP), enabling MCP-aware agents and tools to call Unstructured ETL operations.  
  - Works as a data-access and transformation layer between raw content sources and LLM applications.

- **Static server URL**  
  - Single shared MCP endpoint:  
    - `https://mcp.pipedream.net/v2`  
  - Same URL for all supported MCP clients; configuration is client-agnostic.

- **Client integration support (conceptual)**  
  - Designed to be added to various MCP-compatible chat or agent clients.  
  - Configuration is managed per client, with additional details available on the external configuration page (not reproduced here).

- **Hosted by Pipedream Connect**  
  - The MCP server is run via Pipedream’s infrastructure, so users interact only with the MCP endpoint and authentication when adding it to their app.

> Note: The website content does not list specific ETL pipeline types, document formats, or detailed operations; only the general capability to run unstructured data ETL for LLM preparation is explicitly stated.

---

## Technical Details
- **MCP Endpoint:** `https://mcp.pipedream.net/v2`  
- **Protocol:** Model Context Protocol (MCP)  
- **Authentication:** Performed when adding the server to an MCP-compatible application (details not specified in the provided content).

---

## Pricing
The provided content does not specify any pricing information or plans for the Unstructured MCP Server. Users should refer to the source URL or Pipedream/Unstructured documentation for current pricing details.
