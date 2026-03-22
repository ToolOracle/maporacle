# 🗺️ mapOracle

**Consumer MCP Server** — 12 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-12-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Free-2196F3?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/map/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "maporacle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/map/mcp/"]
    }
  }
}
```

## Tools (12)

| Tool | Description |
|------|-------------|
| `map_geocode` | Convert any address, city, or place name to coordinates (lat/lon). Returns full  |
| `map_reverse` | Convert coordinates to address (reverse geocoding). Returns street, city, postco |
| `map_route` | Calculate driving, walking or cycling route between two places. Returns distance |
| `map_distance` | Straight-line distance between two locations in km, miles, and nautical miles. |
| `map_places` | Find nearby POIs: restaurants, hotels, hospitals, cafes, banks, pharmacies, muse |
| `map_search_address` | Fuzzy address search returning multiple candidates with coordinates. |
| `map_elevation` | Get elevation/altitude in meters for any location. |
| `map_country` | Country information: capital, population, area, currencies, languages, borders,  |
| `map_timezone` | Get timezone for any location or coordinates. |
| `map_place_detail` | Detailed information about a specific OSM place by ID (from map_places results). |
| `map_isochrone` | Find all reachable locations within N minutes travel time (driving or walking). |
| `health_check` | MapOracle server status and backend connectivity. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 100 calls/day | €0 |
| Pro | 10,000 calls/day | €29/month |
| Enterprise | Unlimited | Custom |

> Free tier includes all tools with rate limiting. Upgrade for higher limits and priority support.

## Part of ToolOracle

mapOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.



**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/map/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
