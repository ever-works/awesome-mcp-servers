# YouTube Transcripts (AlphaOSINT)

A hosted MCP server that gives an assistant the spoken text of YouTube videos. It pins one Apify Actor, `johnvc/youtubetranscripts`, as a single typed tool, so nothing has to be installed or self-hosted.

## Connection

- Hosted endpoint: `https://mcp.apify.com/?tools=johnvc/youtubetranscripts`
- Transport: Streamable HTTP
- Authentication: Apify OAuth, or an `Authorization: Bearer <APIFY_TOKEN>` header
- Setup notes: https://github.com/johnisanerd/alphaosint-mcp-servers/tree/main/servers/youtube-transcripts
- Actor page: https://apify.com/johnvc/youtubetranscripts

## What it can do

- Fetch timestamped transcripts for up to 100 video or Shorts URLs in one call
- List a channel's recent uploads and fetch their transcripts
- Pick a preferred language, prefer manual or auto-generated captions, or translate to another language
- Add SRT or VTT output, or list which transcript languages a video has without fetching them
- Attach video metadata such as title, description and channel

## Pricing

Each call runs on the user's own Apify account and is billed per video processed. Current prices are on the Actor page.
