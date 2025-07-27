Install this MCP server by adding the following  JSON code to your configuraiton file:

```json
{
  "mcpServers": {
    "chess": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/profiseeARH/chess-mcp.git",
        "chess"
      ]
    }
  }
}
```
