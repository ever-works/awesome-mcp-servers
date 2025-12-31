# Ollama MCP Server

An MCP server that lets MCP-compatible clients run and interact with local large language models managed by Ollama.

- **Website / Source**: https://mcp.pipedream.com/app/ollama  
- **Category**: AI Integration – MCP Servers  
- **Tags**: LLM, local-models, AI-platform

## Features

### MCP Server & Connection
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
- Works with MCP-compatible chat clients (e.g., ChatGPT via MCP)  
- Authentication handled when adding the server to your application  
- Central configuration via the Pipedream MCP configuration page

### Model Management Tools (Actions)
10 actions are exposed as MCP tools:

1. **Show Model Information**  
   - Retrieve detailed information about a model  
   - Includes model details, Modelfile, template, parameters, license, and system prompt

2. **Push Model to Library**  
   - Upload a model to the Ollama model library  
   - Requires an ollama.ai account and a configured public key

3. **Pull Model**  
   - Download a model from the Ollama library  
   - Cancelled downloads resume from where they left off  
   - Multiple calls share the same download progress

4. **List Local Models**  
   - List all models available locally on the Ollama instance

5. **Generate Embeddings**  
   - Generate vector embeddings from a specified model

6. **Generate Completion**  
   - Create text completions for a given prompt using a selected model

7. **Generate Chat Completion**  
   - Generate the next message in a chat-style interaction with a selected model

8. **Delete Model**  
   - Delete a model and its related data from the local environment

9. **Create Model**  
   - Create a new model from a Modelfile

10. **Copy Model**  
    - Duplicate an existing model under a new name

## Integration & Usage
- Connect an Ollama environment via Pipedream MCP  
- Add the MCP server URL to supported chat clients (e.g., ChatGPT MCP)  
- Use exposed tools to manage models and run LLM operations from within the client

## Pricing
No pricing information is provided in the available content.