# mcp-chaos-index

chaos-index MCP — wraps StupidAPIs (requires X-API-Key)

Part of the [Pipeworx](https://pipeworx.io) open MCP gateway.

## Tools

| Tool | Description |
|------|-------------|
| `chaos_index_calculate` | Combines Bitcoin price, ISS coordinates, city temperatures, earthquake magnitude, and lunar phase into a single chaos score. Methodology available upon request. Please do not request it. |

## Quick Start

Add to your MCP client config:

```json
{
  "mcpServers": {
    "chaos-index": {
      "url": "https://gateway.pipeworx.io/chaos-index/mcp"
    }
  }
}
```

Or use the CLI:

```bash
npx pipeworx use chaos-index
```

## License

MIT
