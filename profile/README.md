<img src="https://graphtia.com/brand/graphtia-mark.png" alt="Graphtia logo" width="64" />

# Graphtia

**Understand what a code change could affect before you make it.**

Graphtia Explorer builds a local map of your codebase. Start with a function, see who calls it, follow the relationships across your project, and open the source behind each result. You can work in the desktop app or ask a connected coding agent to query the same index.

**[Download Explorer Free](https://graphtia.com/downloads)** · [Installation guide](https://graphtia.com/docs/installing-explorer) · [Documentation](https://graphtia.com/docs)

**Public beta for Windows x64 and Ubuntu x64.** No invitation is required. Sign in with a free account after installing. [Explorer Free](https://graphtia.com/docs/early-access) supports two local workspaces per installation and up to 100,000 source lines per workspace.

## What you can do today

**Already in the public beta: Explorer Code Context.** Use focused code navigation and relationship views to investigate a symbol, and check which indexed revision the source evidence comes from. [See it in Explorer](https://graphtia.com/docs/explorer-overview).

- **Trace a change.** Search for files and symbols, follow callers, callees, and dependencies, then inspect potential impact and relevant tests. The graph, source, and inspector stay together as you investigate.
- **Follow a feature across layers.** Trace supported relationships from a client to an API handler or database reference. Inspect OpenAPI declarations and PostgreSQL, MySQL, or SQLite schemas alongside code and indexed project docs.
- **Check the evidence.** See the source locations and indexed revision behind a result, inspect structural findings, and follow recorded agent queries back to their targets in Explorer.
- **Work across languages.** Explore TypeScript/JavaScript, Rust, Go, Java, C#, Python, PHP, and more, including supported patterns in React/Next.js, Spring, ASP.NET Core, and Django. [Check language and framework coverage](https://graphtia.com/docs/language-support).

[![Explorer's split view showing the checkout service graph, verified TypeScript source, and inspector](https://graphtia.com/product/explorer-guide-20261103/explorer-selected-module-windows.jpg)](https://graphtia.com/docs/explorer-overview)

Explorer shows static relationships, not a runtime trace. When a result depends on a particular indexed revision or a relationship cannot be resolved, read the source evidence before relying on it. [See what's included in the public beta](https://graphtia.com/changelog/0.1.101).

## Supported coding agents and clients

**Native integrations:** Codex, Claude Code, OpenCode, Antigravity, VS Code with GitHub Copilot, Devin Desktop, and MiniMax Code.

**Universal MCP:** Other coding clients can connect if they support a local MCP server over stdio. [See integration and setup guides](https://graphtia.com/docs/integrations).

Clients get read-only access to the workspaces you approve. They can search symbols, follow callers and dependencies, inspect potential impact and related-test candidates, and look up supported API contracts, database declarations, and indexed docs. For example: *Which functions call this symbol, what tests should I look at, and which source lines support the answer?*

## What we're working on

**Next Explorer update:** We're refining the desktop interface, deepening semantic analysis so Explorer can resolve more code relationships, and working to shorten indexing times. These improvements are in development and planned for an upcoming update.

**Further out:** [Graphtia Governance](https://graphtia.com/docs/governance-overview) is a separate product direction. It is not part of the next Explorer update and is not publicly available.

[Public roadmap](https://graphtia.com/roadmap) · [Changelog](https://graphtia.com/changelog) · [Website](https://graphtia.com/) · [Contact](https://graphtia.com/contact)
