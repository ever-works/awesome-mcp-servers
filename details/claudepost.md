## ClaudePost

### Description
ClaudePost is an open-source Model Context Protocol (MCP) server that integrates Gmail with Claude Desktop, enabling email management via natural language conversations. It allows users to search, read, compose, and send emails securely from within an MCP-compatible Claude client.

### Features
- **MCP-based email server**
  - Exposes email functionality to Claude via the Model Context Protocol (MCP).
  - Runs as a server that Claude Desktop connects to via configuration.

- **Gmail integration**
  - Connects to a Gmail account for managing emails (searching, reading, composing, and sending).

- **Natural language email control**
  - Perform email-related tasks by chatting with Claude instead of using a traditional email UI.

- **Email search**
  - Search emails based on natural language queries (e.g., find specific messages, threads, or time ranges).

- **Email reading**
  - Retrieve and display email contents.
  - Navigate and inspect specific messages from search results.

- **Email composition and sending**
  - Compose new emails via natural language instructions.
  - Send emails directly through Claude once composition is confirmed.

- **Email statistics**
  - Query basic statistics about your mailbox (e.g., counts or summaries, as demonstrated in usage examples).

- **Secure operation**
  - Uses environment-based configuration (via `.env`) for sensitive information.
  - Designed to keep email access scoped to the configured account and MCP server.

### Prerequisites
- Claude for Desktop installed and updated to the latest version.
- `uv` installed (for Python environment and dependency management).
- Ability to create and manage a `.env` file for configuration.

### Setup & Integration
1. **Install tools**
   - Install `uv`.

2. **Clone and configure the project**
   - Clone the `claude-post` repository.
   - Create a `.env` file in the project root and provide the required configuration values (e.g., credentials and settings needed by the email client/Gmail integration).

3. **Configure Claude Desktop**
   - Ensure Claude for Desktop is installed and up to date.
   - Open the Claude Desktop configuration file.
   - Add the MCP server configuration pointing to your local `claude-post` project path (e.g., `/path/to/claude-post`).
   - Adjust any user-specific paths such as `/Users/username` as needed.
   - Restart Claude Desktop after updating the configuration.

4. **Run the server**
   - The MCP server is started and managed automatically by Claude Desktop based on the configuration.

### Usage
- Interact with the MCP server entirely through Claude Desktop using natural language.
- Supported example actions include:
  - **Search emails** (e.g., "Search my inbox for messages from [sender] last week").
  - **Read email content** from search results or specific threads.
  - **View email statistics** about your mailbox.
  - **Compose and send emails** by describing recipients, subject, and body in conversation.

### Pricing
- No pricing information is provided in the available content.
- The project is open source; the specific license terms are defined in the repository’s `LICENSE` file.