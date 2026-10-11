# PHARN Dev

**Ship it right. See what's running.**

We build open-source developer tools in two areas: shipping features with AI agents (PHARN) and seeing what a Node.js app is doing (Argus).

## Our projects

### [PHARN](https://github.com/pharn-dev/pharn-oss) — Ship features right with AI agents

Describe a feature and PHARN plans, builds and verifies it. The spec, plan and checks stay in your repo, so months later you can still answer "why was it done this way?"

PHARN is an open-source workflow for Claude Code. A feature moves through spec, plan, test, build and verify, and each step leaves readable Markdown next to your code.

- **Built to ship right:** every acceptance criterion gets a test that must fail before any code exists, and deterministic checks run on the result. Model review stays advisory.
- **Keep the trail in Git:** readable Markdown and machine-readable run records.
- **Choose your workflow:** run individual stages or an unattended local implementation loop.

```bash
npx @pharn-dev/pharn@latest init
```

[Explore PHARN](https://github.com/pharn-dev/pharn-oss) · [CLI and installation](https://github.com/pharn-dev/pharn-cli)

### [Argus](https://github.com/pharn-dev/argus) — See what's running in your Node.js app

Argus is for a quick look at a live Node.js process: one line, in-process, no account.

Its zero-external-dependency agent captures **event loop delay, memory usage, garbage collection, stream backpressure, and HTTP request traces** and writes them as NDJSON. An optional collector and dashboard, shipped in the same package, turn that into time windows, alerts and a live page in your browser.

- **Inspect a running process:** find performance signals and request-level context.
- **No account, no backend:** collect data locally and view it in your browser.
- **Integrate when useful:** export metrics and traces through OpenTelemetry.

**Status:** Pre-release. Argus can be built and tried from source; it is not yet published to npm.

[Explore Argus](https://github.com/pharn-dev/argus)

## Ecosystem

- **[pharn-cli](https://github.com/pharn-dev/pharn-cli):** install and update PHARN in existing projects.
- **[skills](https://github.com/pharn-dev/skills):** Claude Code plugin marketplace that keeps a project's PHARN installation current and adds Node.js runtime diagnosis with Argus (Argus also on Codex).

## Our approach

We favor behavior you can read over black boxes, claims you can check over claims you have to trust, and tools that fit the workflow you already have.

## Get involved

Explore the repositories, read their documented limitations, report a concrete issue, or contribute an improvement. Each product's README is the best place to start.
