# zhc-discovery-mcp

MCP tool discovery engine u2014 semantic search across 36 ZHC products. Find the right tool for any task. Always free.

## Quick Start

```bash
git clone https://github.com/marilynceo/zhc-discovery-mcp.git
cd zhc-discovery-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://zhc-discovery.zhc-mcp.org

## Tools

| Tool | Description |
|------|-------------|
| `discover_tools` | Search query — keywords that match against product name, description, and tags (e.g. 'compliance germany', 'invoice tax') |
| `list_categories` | List all product categories with the number of products in each and a short description. |
| `get_product` | Exact product name (e.g. 'de-dsgvo-check-mcp', 'cloudcost-mcp') |

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/zhc-discovery-mcp

# Or connect directly via MCP client
# Endpoint: https://zhc-discovery.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
