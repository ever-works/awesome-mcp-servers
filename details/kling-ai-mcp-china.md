# Kling AI MCP (China)

Official hosted China-region image and video generation, reference workflows and task tracking through MCP.

## Connection and installation
- Endpoint: `https://klingai.com/mcp/plugin`
- Transport: Streamable HTTP
- Authentication: OAuth with the matching China account
- Claude Code: `claude mcp add --transport http kling-ai-china https://klingai.com/mcp/plugin`
- Official integration/setup documentation: https://github.com/klingai-dev/openclaw-plugin

## Usage and account requirements
Generate a product image from text, create a reference-guided video, or retrieve progress using the returned task ID. Subject and motion-control workflows, models and parameters depend on live server tools and account permissions. Prompts and selected references are sent to Kling for processing.

Generation consumes account credits. China and Global accounts, credits and task IDs are separate; authorize against the matching regional endpoint. No free-generation allowance or cross-region sharing is promised.

The linked repository provides client integration and documentation, not hosted-server source. Hosted-service terms apply; no hosted-service open-source license is asserted.
