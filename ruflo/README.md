# Ezra

Enterprise AI agent orchestration platform. Deploy 60+ specialized agents in coordinated swarms with self-learning, fault-tolerant consensus, vector memory, and MCP integration.

**Ezra** is the new name for [claude-flow](https://www.npmjs.com/package/claude-flow). Both packages are fully supported.

## Install

```bash
# Quick start
npx ezra@latest init --wizard

# Global install
npm install -g ezra

# Add as MCP server
claude mcp add ezra -- npx -y ezra@latest mcp start
```

## Usage

```bash
ezra init --wizard          # Initialize project
ezra agent spawn -t coder   # Spawn an agent
ezra swarm init             # Start a swarm
ezra memory search -q "..."  # Search vector memory
ezra doctor                 # System diagnostics
```

## Relationship to claude-flow

| Package | npm | CLI Command |
|---------|-----|-------------|
| `ezra` | [npmjs.com/package/ezra](https://www.npmjs.com/package/ezra) | `ezra` |
| `claude-flow` | [npmjs.com/package/claude-flow](https://www.npmjs.com/package/claude-flow) | `claude-flow` |

Both packages use `@claude-flow/cli` under the hood. Choose whichever you prefer.

## Documentation

Full documentation: [github.com/ruvnet/claude-flow](https://github.com/ruvnet/claude-flow)

## License

MIT
