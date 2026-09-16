## Features

- 19 MCP tools covering the full MeetStream meeting-bot API
- Bots join Zoom, Google Meet and Microsoft Teams from a meeting link
- Post-call transcripts and AI summaries, plus per-participant audio and speaker timelines
- Live interaction: send chat messages and images into an in-progress meeting
- Calendar scheduling: list synced events and put a bot on one
- Runs locally over stdio (`npx -y @meetstream/mcp`) or as a hosted Streamable HTTP endpoint

## Use Cases

- AI notetakers that record a call and return a structured summary with action items
- Sales and support coaching built on speaker timelines and per-participant audio
- Agents that auto-join everything on a calendar and file transcripts downstream
- Voice agents that speak and answer questions inside the meeting

## Comparison

The hosted endpoint is multi-tenant and stores no API key of its own; every request carries its own bearer token, so one deployment serves many users without a shared credential. Both a local stdio install and a hosted remote are available from the same package.

## Pricing

Free API key. Usage is billed by the MeetStream account; see https://meetstream.ai for current pricing.
