# OpenRouter MCP Server

## Description
OpenRouter MCP Server is an MCP (Model Context Protocol) server that provides a unified interface to multiple LLM providers and models via OpenRouter’s routing layer. It allows applications and chat clients to access OpenRouter models through a single, static MCP server endpoint.

## Key Details
- **Category:** AI Integration – MCP Servers  
- **Brand:** OpenRouter  
- **Interface Type:** MCP server over a static URL  
- **Static MCP URL:** `https://mcp.pipedream.net/v2`

## Features
- **Unified LLM Access via OpenRouter**  
  - Connects to OpenRouter to access multiple LLM providers and models through one MCP server.  
  - Uses OpenRouter’s routing layer to standardize how different models are called.

- **Static MCP Server Endpoint**  
  - Single server URL (`https://mcp.pipedream.net/v2`) used across supported clients.  
  - Authentication handled when adding the server to each application or client.

- **Client Integration**  
  - Instructions and guides available for integrating with chat clients such as ChatGPT (OpenAI) via MCP.  
  - Additional configuration options available on a dedicated configuration page.

- **Available Tools (Actions)**  
  The MCP server exposes three main actions as tools:
  1. **Send Completion Request**  
     - Sends a completion request to a selected model in text-only format.  
     - Suitable for typical text completion use cases (e.g., prompts that expect a single text response).

  2. **Send Chat Completion Request**  
     - Sends a chat-style completion request to a selected model.  
     - Supports multi-turn, chat-oriented interactions where messages are structured as roles (e.g., user, assistant, system).

  3. **Retrieve Available Models**  
     - Returns a list of models available through the OpenRouter API.  
     - Allows clients to dynamically discover which models can be used for completion or chat completion.

## Configuration & Setup
- **Configure OpenRouter**  
  - Users connect their OpenRouter account and then select their client to begin using the MCP server.  
  - Sign-in is required to connect OpenRouter and manage accounts.  
- **Add the Server to Your App**  
  - Copy the static MCP server URL.  
  - Add the server to supported chat clients or applications following per-client guides.

## Pricing
The provided content does not include any pricing details or plan information for the OpenRouter MCP Server.