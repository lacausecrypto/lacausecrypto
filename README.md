<div align="center">

# lacause

Open-source AI infrastructure and data-facing MCP servers.

I build two kinds of projects: the tooling around agents, and the MCP servers that expose usable domain data to those agents.

</div>

## Infrastructure

### [OCC](https://github.com/lacausecrypto/OCC)

YAML-first LLM orchestrator for multi-model chains with auto-parallelism, pre-tools, MCP integration, REST APIs, and a React canvas.

`3243 tests` `29 MCP tools` `106 REST endpoints` `6 providers`

### [mcp-conduit](https://github.com/lacausecrypto/mcp-conduit)

Open-source MCP gateway for routing, caching, auth, rate limiting, guardrails, and observability between agents and MCP servers.

`0.02ms overhead` `46K+ RPS cache hits` `1341 tests` `HTTP + stdio`

### [apple-mcp-server](https://github.com/lacausecrypto/apple-mcp-server)

macOS automation MCP server with explicit permission levels, audit logging, and structured tool access to Apple apps and system controls.

`31 tools` `303 actions` `permission model` `audit log`

## Data Servers

### [mcp-belgium](https://github.com/lacausecrypto/mcp-belgium)

Aggregated MCP server for Belgian public APIs: transport, official statistics, addresses, weather, air quality, open data, and geospatial services.

`16 APIs` `63 tools` `single entry point` `Belgian public data`

### [mcp-nbb](https://github.com/lacausecrypto/mcp-nbb)

MCP server for the National Bank of Belgium SDMX statistical API, with a bundled catalogue so LLMs can discover and query dataflows cleanly.

`221 dataflows` `6 tools` `3 resources` `14 categories`

### [mcp-sports-hub](https://github.com/lacausecrypto/mcp-sports-hub)

Unified MCP server for sports data across scores, stats, odds, esports, and college sports.

`29 providers` `319 tools` `70+ sports`

### [mcp-new-caledonia](https://github.com/lacausecrypto/mcp-new-caledonia)

Compact MCP server for New Caledonia public datasets, covering companies, employment, weather, mining, environment, population, and transport.

`10 modules` `29 tools` `data.gouv.nc`

### [mcp-poetrydb](https://github.com/lacausecrypto/mcp-poetrydb)

Compact MCP server for exploring classic poetry through PoetryDB with catalog, search, and discovery tools.

`12 tools` `catalog + search + discovery` `no auth`

## How I Build

- explicit configuration over hidden framework magic
- benchmarked claims when performance is part of the pitch
- practical MCP installs with clear client setup paths
- documentation that states limits instead of hiding them
- domain servers that help the LLM discover capabilities before calling tools

