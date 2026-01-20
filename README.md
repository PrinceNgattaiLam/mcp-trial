# mcp-trial
A small project exploring Model Context Protocol (MCP) integration with the Anthropic API.

## Overview

This project demonstrates basic MCP client-server communication using Python. It includes a client, server, and main entry point for testing the integration.

## Requirements

- Python 3.10+
- Dependencies: `anthropic`, `httpx`, `mcp[cli]`, `python-dotenv`

## Setup

1. Install dependencies:
   ```bash
   uv sync
   ```

2. Create a `.env` file with your Anthropic API key:
   ```
   ANTHROPIC_API_KEY=your_key_here
   ```

## Running

Execute the main script:
```bash
python main.py
```

## Files

- `main.py` - Entry point
- `server.py` - MCP server implementation
- `client.py` - MCP client implementation