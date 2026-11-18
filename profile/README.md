<p align="center">
  <img src="https://raw.githubusercontent.com/Canary-ECAD/.github/main/assets/canary-ecad.png" width="220" alt="Canary E-cad — canary drawn as an industrial electrical schematic"/>
</p>

<h1 align="center">Canary E-cad</h1>

<p align="center">
  ⚡ Practical tools for <b>electrical CAD (ECAD)</b> workflows.<br/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-active-F26419?style=flat-square"/>
  <img src="https://img.shields.io/badge/offline_first-14212B?style=flat-square"/>
  <img src="https://img.shields.io/badge/your_data_stays_yours-0C1F33?style=flat-square"/>
</p>

---


## Projects

| Project | What it does |
|---|---|
| [**eplan-mcp**](https://github.com/Canary-ECAD/eplan-mcp) | MCP server that lets Claude Code, Codex, Cursor or any MCP client drive a running EPLAN Electric P8 (2.9 to 2027): 282 tools for actions, C# scripts, the live DataModel and exports. |
| [**eplan-scripting-skill**](https://github.com/Canary-ECAD/eplan-scripting-skill) | Agent skills that teach your AI to write correct EPLAN code: C# scripting, the EPLAN API, Remote Client and the parts database. |
| [**eec-pro-skill**](https://github.com/Canary-ECAD/eec-pro-skill) | Agent skill for EPLAN EEC Pro: mechatronic model, typicals, formulas, EOX files, Groovy actions and the Job Server. |
| [**eplan-cloudflare-rags**](https://github.com/Canary-ECAD/eplan-cloudflare-rags) | Public documentation search (MCP + REST) for EPLAN Electric P8 2026/2027 and EEC Pro, plus visual symbol search. |
| [**ecad-view**](https://github.com/Canary-ECAD/ecad-view) | Open-source viewer for EPLAN projects (`.epdz`) and 3D parts (`.e3d`) |

### Quick start

```
/plugin marketplace add Canary-ECAD/eplan-mcp
/plugin install eplan@eplan-tools
```

Docs and guides: **[covaga.dev](https://covaga.dev)** · Contact: [hello@covaga.xyz](mailto:hello@covaga.xyz)

## Status

In use on real EPLAN projects. eplan-mcp is at v2.0.0 and its C# script host runs on EPLAN 2026
and 2027+. The skills install as Claude Code plugins from one marketplace, `eplan-tools`. Every
change lands through a pull request with tests, and releases are tagged with notes on what changed.

---

<p align="center"><sub>Canary E-cad is an independent project and is not affiliated with, endorsed by, or connected to any E-CAD platform vendor.</sub></p>
