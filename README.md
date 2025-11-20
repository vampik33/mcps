# MCPS - MCP Servers Bundle

A Claude Code plugin that exposes three MCP (Model Context Protocol) servers: context7, sequential-thinking, and serena.

## Overview

This plugin is a simple configuration wrapper that makes three external MCP servers available to Claude Code:

- **context7**: Advanced context management MCP server
- **sequential-thinking**: Sequential reasoning and thought process MCP server
- **serena**: Serena MCP server functionality

The plugin doesn't implement any custom logic - it simply configures Claude Code to use these existing MCP servers.

## Prerequisites

Before using this plugin, ensure that the following MCP server scripts are installed and executable:

- `~/.claude/mcp/context7.sh`
- `~/.claude/mcp/sequential-thinking.sh`
- `~/.claude/mcp/serena.sh`

Make sure they are executable:
```bash
chmod +x ~/.claude/mcp/context7.sh
chmod +x ~/.claude/mcp/sequential-thinking.sh
chmod +x ~/.claude/mcp/serena.sh
```

## License

MIT License - see LICENSE file for details

## Author

Vladislav Dobromyslov

## Changelog

### 1.0.0 (Initial Release)

- Plugin configuration for context7, sequential-thinking, and serena MCP servers
- Simple wrapper with no custom implementation
- Ready to use with existing MCP server installations
