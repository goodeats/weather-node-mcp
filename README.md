# Weather Node MCP Server

Following the [MCP Quickstart Tutorial](https://modelcontextprotocol.io/quickstart/server#node).

## Setup

```bash
npm install
```

## Usage

```bash
node index.js
```

## Project Structure

- `index.js` - Main MCP server implementation
- `package.json` - Dependencies and scripts

## How to use

### Build and run the server

```bash
npm run build
node build/index.js
```

### Add to Claude Desktop

- Go to Claude Desktop settings
- Developer
- Edit Config: `claude_desktop_config.json`
- Open with preferred editor
- Paste the following:

```json
{
  "mcpServers": {
    "weather-node": {
      "command": "node",
      "args": ["/PATH/TO/HERE/weather-node-mcp/build/index.js"]
    }
  }
}
```
