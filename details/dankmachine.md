# DankMachine

Meme soundboard for AI agents with 38k meme sound effects: find a reaction sound for a moment, search by name, mood or use case, see what is trending, and play sounds locally. No authentication.

## Basic Info

- **Name:** DankMachine
- **Category:** Media Processing MCP Servers
- **Source URL:** https://github.com/HalberdLLC/dank-meme-sounds
- **MCP Endpoint:** `https://dankmachine.com/mcp`
- **Tags:** `audio`, `sound-effects`, `memes`, `remote`

## Features

- `find_reaction_sound`: describe a situation and get fitting meme sounds.
- Search and browse by name, mood, use case, category or platform.
- Trending sounds from real plays (1h / 24h / 7d), plus random picks.
- Each result carries the meme's context (origin when known, how it is used, moods, use cases) and an MP3 URL.
- The local npm package adds `play_sound` to play a sound on your speakers.

## Setup

- Add `https://dankmachine.com/mcp` as a remote MCP server (Streamable HTTP). No authentication or API key is required.
- Or run locally: `npx -y dank-meme-sounds` (MIT, npm package `dank-meme-sounds`).
- Docs: https://dankmachine.com/developers/
