# AnswerLine MCP Server

## Overview

AnswerLine is a hosted remote Model Context Protocol server by Quantive Bt. that returns what major AI engines actually answer for a keyword or question, as structured JSON. It covers ChatGPT, Gemini, and Google (Search with AI Overviews, AI Mode, and News), with results localized by country and every answer carrying the source pages the engine cited.

## Features

### AI Answer Retrieval
- **Multi-engine answers**: Query ChatGPT, Gemini, Google AI Overviews, Google AI Mode and Google News through one server.
- **Cited sources**: Each answer includes the URLs the engine used, enabling citation and share-of-voice tracking.
- **Country targeting**: Answers can be localized to a specific market for international SEO and GEO work.
- **AI Mode fan-out**: Returns the search queries Google AI Mode decomposed a question into.

### Integration
- **Transport**: Streamable HTTP at `https://mcp.answerline.dev/mcp`.
- **Auth**: `initialize` and `tools/list` are open; tool calls require an `X-Api-Key` header. A free tier is available at answerline.dev.
- **Registry**: Listed on the official MCP Registry as `dev.answerline/answerline`.

## Use Cases

- Monitoring brand and product visibility inside AI-generated answers.
- Tracking which domains AI engines cite for a niche's money keywords.
- Powering SEO/GEO dashboards and agents with real AI answer data instead of scraped HTML.
- Comparing how ChatGPT, Gemini and Google answer the same prompt.
