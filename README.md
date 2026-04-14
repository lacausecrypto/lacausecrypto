<div align="center">

# lacause

Open-source AI infrastructure for agent workflows, MCP tooling, and local automation.

<a href="https://github.com/lacausecrypto/OCC"><img src="https://img.shields.io/badge/OCC-YAML_orchestration-000000?style=for-the-badge&logo=anthropic&logoColor=D97757" /></a>
<a href="https://github.com/lacausecrypto/mcp-conduit"><img src="https://img.shields.io/badge/MCP_Conduit-gateway-000000?style=for-the-badge&logo=zap&logoColor=FBBF24" /></a>
<a href="https://github.com/lacausecrypto/mcp-sports-hub"><img src="https://img.shields.io/badge/Sports_Hub-319_tools-000000?style=for-the-badge&logo=nba&logoColor=FF6600" /></a>
<a href="https://github.com/lacausecrypto/apple-mcp-server"><img src="https://img.shields.io/badge/Apple_MCP-303_actions-000000?style=for-the-badge&logo=apple&logoColor=white" /></a>

<sub><a href="https://www.npmjs.com/package/occ-orchestrator">occ-orchestrator</a> · <a href="https://www.npmjs.com/package/mcp-conduit">mcp-conduit</a> · <a href="https://www.npmjs.com/package/mcp-sports-hub">mcp-sports-hub</a> · <a href="https://twitter.com/lacausecrypto">@lacausecrypto</a></sub>

</div>

## What I Build

I build tools that make AI systems easier to run outside demos:

- YAML-first orchestration instead of framework boilerplate
- MCP gateways with caching, auth, rate limiting, and guardrails
- large practical MCP servers with clear install and operating paths
- local-first automation for macOS and developer workflows

## Featured Projects

### [OCC](https://github.com/lacausecrypto/OCC)

Orchestrator Chain Chimera is a YAML-first runtime for multi-model LLM workflows with parallel execution, pre-tools, REST APIs, and a React dashboard.

`3243 tests` `29 MCP tools` `106 REST endpoints` `6 providers`

```bash
npm install -g occ-orchestrator
occ init my-project && cd my-project
occ start
```

### [MCP Conduit](https://github.com/lacausecrypto/mcp-conduit)

An open-source MCP gateway that sits between agents and servers to add routing, caching, auth, guardrails, and observability without changing application code.

`0.02ms overhead` `1341 tests` `HTTP + stdio` `production-focused`

### [Sports Hub MCP Server](https://github.com/lacausecrypto/mcp-sports-hub)

A unified MCP server that aggregates sports data across 29 providers and exposes a single tool surface for scores, stats, odds, esports, and college sports.

`29 providers` `319 tools` `70+ sports`

### [Apple MCP Server](https://github.com/lacausecrypto/apple-mcp-server)

A macOS-focused MCP server that exposes Apple apps and system controls with permission levels, audit logging, and explicit safety boundaries.

`31 tools` `303 actions` `permission model`

## Principles

- explicit configuration over hidden magic
- benchmarked claims over vague performance promises
- honest documentation about security and limits
- tools that work well on one machine before pretending to be a platform

## Stack

`TypeScript` `Node.js` `React` `SQLite` `Python` `Claude` `MCP`
