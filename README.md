<div align="center">

# lacause

Open-source AI infrastructure and data-facing MCP servers.

I build two kinds of projects: the tooling around agents, and the MCP servers that expose usable domain data to those agents.

</div>

## Infrastructure

| Project | Focus | Signals |
| --- | --- | --- |
| [OCC](https://github.com/lacausecrypto/OCC) | YAML-first LLM orchestrator with auto-parallelism, pre-tools, MCP, REST APIs, and React canvas | `3243 tests` `29 MCP tools` `106 REST endpoints` `6 providers` |
| [mcp-conduit](https://github.com/lacausecrypto/mcp-conduit) | MCP gateway for routing, caching, auth, rate limiting, guardrails, and observability | `0.02ms overhead` `46K+ RPS cache hits` `1341 tests` `HTTP + stdio` |
| [apple-mcp-server](https://github.com/lacausecrypto/apple-mcp-server) | macOS automation MCP server with permission controls and audit logging | `31 tools` `303 actions` `permission model` `audit log` |
| [mcp-sophon](https://github.com/lacausecrypto/mcp-sophon) | Deterministic context layer for MCP agents — prompt / memory / code / delta / output compression, BGE semantic retrieval | `67% savings` `60% LOCOMO (=mem0)` `206 tests` `20 output filters` |

## Data Servers

| Project | Focus | Signals |
| --- | --- | --- |
| [mcp-belgium](https://github.com/lacausecrypto/mcp-belgium) | Aggregated Belgian public APIs: transport, statistics, addresses, weather, air quality, open data, geospatial | `16 APIs` `63 tools` `single entry point` |
| [mcp-nbb](https://github.com/lacausecrypto/mcp-nbb) | National Bank of Belgium SDMX dataflows with bundled discovery catalogue | `221 dataflows` `6 tools` `3 resources` `14 categories` |
| [mcp-sports-hub](https://github.com/lacausecrypto/mcp-sports-hub) | Unified sports data server across scores, stats, odds, esports, and college sports | `29 providers` `319 tools` `70+ sports` |
| [mcp-new-caledonia](https://github.com/lacausecrypto/mcp-new-caledonia) | New Caledonia public datasets across companies, weather, mining, environment, population, transport | `10 modules` `29 tools` `data.gouv.nc` |
| [mcp-poetrydb](https://github.com/lacausecrypto/mcp-poetrydb) | PoetryDB server for catalog, search, and discovery workflows | `12 tools` `catalog + search + discovery` `no auth` |
| [datamuse-mcp](https://github.com/lacausecrypto/datamuse-mcp) | Lexical search server for synonyms, antonyms, rhymes, autocomplete, and word metadata | `10 tools` `rhymes + synonyms + autocomplete` `Datamuse API` |

## How I Build

- explicit configuration over hidden framework magic
- benchmarked claims when performance is part of the pitch
- practical MCP installs with clear client setup paths
- documentation that states limits instead of hiding them
- domain servers that help the LLM discover capabilities before calling tools
