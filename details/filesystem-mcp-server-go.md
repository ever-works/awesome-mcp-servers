## Overview

Filesystem MCP Server is a high-performance Go implementation providing secure filesystem operations through the Model Context Protocol. It offers comprehensive file and directory management with enterprise-grade security features.

## Features

### File Operations
- Read file contents
- Write and create files
- Update existing files
- Delete files
- Copy and move files
- File metadata access

### Directory Management
- List directory contents
- Create directories
- Remove directories (recursive)
- Directory tree traversal
- Search directories

### Advanced Search
- File name search
- Content-based search
- Regex pattern matching
- Recursive directory search
- Filter by file type
- Date and size filters

### Security Features
- **Path Sanitization**: Prevents directory traversal attacks
- **JWT Authentication**: Secure HTTP transport authentication
- **Access Control**: Configurable base directories
- **Read-only Mode**: Optional restriction to read operations
- **Audit Logging**: Track all file operations

## Go Performance Benefits

- Concurrent file operations
- Low memory footprint
- Fast startup time
- Efficient resource usage
- Native OS integration

## Deployment Options

### Standalone Binary
- Single executable
- No dependencies
- Cross-platform (Linux, macOS, Windows)
- Easy distribution

### Docker Container
- Pre-configured environment
- Volume mounting
- Network isolation
- Easy scaling

### HTTP Transport
- Remote file access
- JWT-based authentication
- RESTful API
- CORS support

## Use Cases

- Secure file management for AI assistants
- Document processing automation
- Log file analysis
- Configuration management
- Backup and sync operations
- Content extraction and indexing
- File system monitoring

## Configuration

### Base Directory
Set allowed base directories for operations:
- Multiple directory support
- Nested directory access
- Symbolic link handling

### Transport Mode
- **Stdio**: Local process communication
- **HTTP**: Remote access with authentication

### Security Settings
- Enable/disable write operations
- Configure allowed paths
- Set maximum file sizes
- Define excluded patterns

## Technical Implementation

Built with Go standard library and optimized for performance. Implements proper file locking, error handling, and resource cleanup.

## Integration

Compatible with Claude Desktop, Cursor, VS Code, and other MCP clients. Supports both local and remote filesystem access through HTTP transport.

## Platform Support

- Linux (all distributions)
- macOS (Intel and Apple Silicon)
- Windows (64-bit)
- Docker containers
- Kubernetes deployments