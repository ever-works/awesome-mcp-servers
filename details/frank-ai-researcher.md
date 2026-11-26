# Frank AI Researcher

Frank is an AI user researcher that runs short voice interviews. Its hosted MCP server lets an assistant create interview studies, publish a voice interviewer link or website widget, and read transcripts. You bring the customers; Frank does not recruit.

## Connection

- Hosted endpoint: `https://api.hifrank.ai/mcp`
- Transport: Streamable HTTP
- Authentication: OAuth 2.1 with PKCE (S256). A Frank account is required.
- Setup documentation: https://www.hifrank.ai/docs/frank-mcp-connector
- MCP Registry: ai.hifrank/frank
- Website: https://www.hifrank.ai
- Usage documentation: https://github.com/nar-vardanyan/frank-mcp

Works with ChatGPT, Claude, Grok and Muse, plus other MCP clients that support remote servers with OAuth.

## What it can do

- Create, edit and list interview studies, and publish a study to get its interviewer link
- Attach a product to a study, and list or create products
- List interviews and read a transcript
- List and configure website-widget formats for a study

MCP is included on every plan, including Free. The Free plan includes 60 voice minutes a month, no card required.

The hosted service is proprietary. The public repository holds usage documentation and MCP metadata; the server runs at api.hifrank.ai.
