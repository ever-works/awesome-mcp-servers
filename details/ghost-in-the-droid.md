# Ghost in the Droid

Gives an AI agent a real Android phone (iPhone opt-in) with 66 MCP tools, a skill hub of 117 replayable skills for 113 apps, and human-in-the-loop steps.

## Basic Info

- **Name:** Ghost in the Droid
- **Category:** OS Automation
- **Source URL:** https://github.com/ghost-in-the-droid/android-agent
- **Website:** https://ghostinthedroid.com
- **Tags:** `android`, `ios`, `mobile`, `python`

## Features

- Android over ADB; iPhone over WebDriverAgent (opt-in).
- 66 MCP tools for reading the screen, tapping, typing and managing apps.
- Skill Hub with 117 skills for 113 apps that replay recorded routes without calling an LLM.
- Human-in-the-loop steps, for example a person solves a captcha and the agent carries on.

## Setup

- Claude Code: `claude mcp add android-agent -- uvx --from ghost-in-the-droid android-agent-mcp`
