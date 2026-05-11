# Overview

A Model Context Protocol (MCP) integration for Minecraft that enables AI assistants to interact with a Minecraft server. This integration allows AI models to observe and interact with the Minecraft world through a bot.

## Features

### Resources
- `minecraft://bot/location` - Current bot position in the world
- `minecraft://bot/status` - Bot connection status

### Tools
- `chat` - Send chat messages to the server
- `jump` - Make the bot jump
- `moveForward` - Make the bot move forward
- `moveBack` - Make the bot move backward
- `turnLeft` - Make the bot turn left
- `turnRight` - Make the bot turn right
- `placeBlock` - Place a block at specified coordinates
- `digBlock` - Break a block at specified coordinates
- `getBlockInfo` - Get information about a block at specified coordinates
- `selectSlot` - Select a hotbar slot (0-8)
- `getInventory` - Get contents of bot's inventory
- `equipItem` - Equip an item by name to specified destination
- `getStatus` - Get bot's current status (health, food, position, etc.)
- `getNearbyEntities` - Get list of nearby entities within range
- `attack` - Attack a nearby entity by name
- `useItem` - Use/activate the currently held item
- `stopUsingItem` - Stop using/deactivate the current item
- `lookAt` - Make the bot look at specific coordinates
- `followPlayer` - Follow a specific player
- `stopFollowing` - Stop following current target
- `goToPosition` - Navigate to specific coordinates

## Installation

### Prerequisites
- Minecraft Launcher
- Node.js 18 or higher
- Claude Desktop App
- Java 21.0.5 (recommended)

### Quick Install (Recommended)
```bash
npx -y @smithery/cli install mcp-minecraft --client claude
```

### Manual Setup
1. Navigate to `~/Library/Application Support/Claude/claude_desktop_config.json`
2. Add the MCP server configuration:
```json
{
  "mcpServers": {
    "mcp-minecraft": {
      "command": "npx",
      "args": [
        "-y",
        "mcp-minecraft@latest",
        "--server-jar",
        "/absolute/path/to/minecraft-server/server.jar"
      ]
    }
  }
}
```

### Server Setup
1. Download Minecraft server v1.21 from mcversions.net/1.21
2. Install Java 21.0.5 if not already installed
3. Create a dedicated directory (e.g., `~/minecraft-server/`)
4. Place the downloaded server.jar file in this directory
5. Note down the absolute path to your server.jar file

### Launch and Connect
1. Start Claude Desktop after completing the configuration
2. Open Minecraft Launcher
3. Install and launch Minecraft Java Edition v1.21
4. Click "Play" and Select "Multiplayer"
5. Click "Add Server"
6. Enter server details:
   - Server Name: Minecraft Server
   - Server Address: localhost:25565
7. Click "Done"

## Technical Details

- Server runs in offline mode for local development
- Default memory allocation: 2GB
- Default port: 25565
- Bot username: MCPBot

## Troubleshooting

### MCP Connection Failed
- Look for lingering Java processes
- Terminate them manually:
  - Windows: Use Task Manager (untested)
  - Mac/Linux: Go to 'Activity Monitor' and 'Force Quit' java
- Restart computer if process termination fails
- Note: Latest version should auto-resolve these issues

### Server Won't Start
- Verify Java is installed
- Check server.jar path is correct
- Ensure port 25565 is available

### Can't Connect to Server
- Verify server is running (check logs)
- Confirm you're using "localhost" as server address
- Check firewall settings

## Logs Location

- Minecraft Server logs: Check the minecraft-server directory
- Claude Desktop logs: ~/Library/Logs/Claude/mcp*.log

## License

This project is licensed under the MIT License - see the LICENSE file for details.
