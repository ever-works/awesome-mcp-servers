# QuestionPunk

QuestionPunk is a survey and research platform with AI-moderated voice and chat interviews. Its hosted MCP server lets an assistant build studies in the user's account instead of writing them out as text.

## Connection

- Hosted endpoint: `https://app.questionpunk.com/api/v1`
- Transport: Streamable HTTP
- Authentication: OAuth with PKCE and automatic client registration; a QuestionPunk account is required.
- Setup documentation: https://www.questionpunk.com/features/mcp-server
- MCP Registry: io.github.questionpunk/questionpunk

## What it can do

- Create a study or start one from a template, add and edit questions, and set display logic on a draft
- Publish a study, which returns the participant link and the editor link
- With permission to read responses: response counts, single responses, reports, cross-tabs and exports

The consent screen lists the permissions the assistant asks for. Access can be removed under Settings > Integrations > Connected apps.

The hosted service is proprietary; there is no public source repository.
