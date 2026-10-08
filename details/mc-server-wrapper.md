## Overview

mc-server-wrapper manages MCP server lifecycles in Python.

## Features

- Script training runs
- Command injection
- Docker support

## Usage

docker run -d -p 25565:25565 -e EULA=TRUE itzg/minecraft-server

Or in Python:

```python
import subprocess
subprocess.run(["java", "-jar", "server.jar", "nogui"])
```

## Pricing

Free and open-source.