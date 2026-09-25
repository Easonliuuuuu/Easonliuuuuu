# Eason Liu

**Software Engineer at Dell** · Taipei, Taiwan

I build release pipelines and deployment tooling for private cloud platforms. My work spans Kubernetes workloads and storage, containerized microservices, and virtual environments that help developers test cluster behavior.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/easonliu-profile/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:easoneastin@gmail.com)

## Open Source

Contributions to upstream projects such as OpenTelemetry: [my pull requests →](https://github.com/search?q=is%3Apr+author%3AEasonliuuuuu+-user%3AEasonliuuuuu&type=pullrequests)

## Projects

### [vsfleet](https://github.com/Easonliuuuuu/vsfleet) · Go

Read-only vSphere estate assessment and diagnostics across every vCenter, from one CLI and terminal UI.

- Queries many vCenters in parallel and returns partial results when a site is unreachable
- Per-context proxy routing (SOCKS5 / HTTP CONNECT) and OS-keyring credentials, no plaintext secrets
- Historical drift tracking in SQLite, RVTools-compatible Excel export and import for migration sizing
- CI with whole-suite coverage, Kubernetes E2E, and a PTY-driven TUI test harness; ships via Homebrew and GitHub Releases

### [flow-code](https://github.com/Easonliuuuuu/flow-code) · TypeScript

A terminal-native node-graph interface for running and observing agentic coding workflows.

- Each step is a live card with status, model, token spend, and streaming output
- Test failures route back upstream with bounded retries; the verdict is an exit code, not an opinion
- Structural approval gates: a graph that can reach git without passing a gate is rejected at load time
- Hard token and time budgets per node and per run

### [FirearmDB-MCP](https://github.com/Easonliuuuuu/FirearmDB-MCP) · Python

A structured reference dataset (616 firearms, 365 cartridges, 407 manufacturers) served as a FastAPI REST API and as an MCP server for agent clients.

## Tools

Go · Python · TypeScript · Bash · Kubernetes · Docker · Ansible · GitHub Actions · OpenTelemetry · VMware vSphere · Linux

## Currently

- Upstreaming vCenter receiver improvements to OpenTelemetry
- Building harness tooling that makes AI coding agents observable and bounded
