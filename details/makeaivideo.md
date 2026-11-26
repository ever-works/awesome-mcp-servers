# MakeAIVideo

MCP server for AI video: agents create finished short-form videos with voiceover, scenes, captions and music, and post them to TikTok, Instagram or YouTube.

## Basic Info

- **Name:** MakeAIVideo
- **Category:** Media Processing MCP Servers
- **Source URL:** https://github.com/makeaivideo-ai/mcp
- **MCP Endpoint:** `https://mcp.makeaivideo.ai`
- **Tags:** `video`, `video-generation`, `remote`

MakeAIVideo is an AI video generator for short-form video. Its MCP server lets Claude, ChatGPT, Cursor and other MCP clients make a video from a prompt or a script: it writes the script, generates AI or stock scenes, adds an AI voiceover, captions and music, and returns the MP4 in 9:16, 1:1 or 16:9. It can also post or schedule the video to TikTok, Instagram, YouTube and other connected social accounts.

- **Endpoint:** `https://mcp.makeaivideo.ai`
- **Transport:** Streamable HTTP (remote, nothing to install), or local stdio with `npx -y @makeaivideo/mcp` and `MAKEAIVIDEO_API_KEY`
- **Authentication:** OAuth 2.1, or a Bearer API key from the MakeAIVideo developer page
- **Pricing:** Needs a MakeAIVideo account; videos use paid credits
- **License:** MIT (stdio server)
- **Official MCP Registry name:** `ai.makeaivideo/video-generator`
- **Documentation:** [MakeAIVideo MCP docs](https://makeaivideo.ai/docs/mcp)

Disclosure: submitted by the maker (MakeAIVideo).
