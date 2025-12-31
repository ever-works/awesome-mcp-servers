# Evernote MCP Server

**Category:** Document Management MCP Servers  
**Brand:** Evernote  
**Source:** https://mcp.pipedream.com/app/evernote

## Description
Evernote MCP Server is an integration that exposes Evernote functionality via the Model Context Protocol (MCP), allowing AI agents and compatible chat clients to create, update, and organize notes and notebooks in an Evernote account.

## Features
- **MCP-compatible endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Works with multiple MCP-capable clients (e.g., ChatGPT / OpenAI clients).

- **Evernote account integration**  
  - Connects to a user’s Evernote account via sign-in.  
  - Allows authenticated operations on notes and notebooks.

- **Available tools / actions**  
  - **Create Note**  
    - Creates a new note in Evernote.  
    - Uses Evernote’s note fields (title, content, notebook association, etc. as supported by the underlying action).  
  - **Update Note**  
    - Updates an existing note in Evernote.  
    - Can modify note content and other editable fields.  
  - **Create Notebook**  
    - Creates a new notebook in Evernote for organizing notes.

- **Client configuration support**  
  - Guidance available for adding the MCP server to supported chat clients (e.g., ChatGPT).  
  - Central configuration documentation via Pipedream’s MCP configuration page.

## Use Cases
- Letting AI agents create and organize Evernote notes during a conversation.  
- Updating existing Evernote notes based on AI-generated content.  
- Programmatically creating notebooks to structure projects, tasks, or knowledge bases.

## Pricing
The provided content does not list any pricing or plans for the Evernote MCP Server. Pricing details, if any, are not specified on this page.