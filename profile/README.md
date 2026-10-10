# PHARN Dev

**Build with evidence. Debug with clarity.**

We build open-source developer tools that make software easier to build, inspect, and debug.

Our projects focus on two practical problems: understanding AI-assisted code changes and diagnosing what happens inside running applications.

## Our projects

### [PHARN](https://github.com/pharn-dev/pharn-oss) — Make AI-assisted changes reviewable

AI agents can write code quickly. PHARN helps you understand **what was requested, what changed, and which checks actually ran**.

PHARN is a repository-local workflow for Claude Code. It records specifications, plans, acceptance tests, checks, and outcomes alongside the code, so important engineering context does not disappear when the chat ends.

- **Keep the trail in Git:** reviewable Markdown and machine-readable run records.
- **Distinguish evidence from judgment:** deterministic checks are clearly separated from model-assisted review.
- **Choose your workflow:** run individual stages or an unattended local implementation loop.

```bash
npx @pharn-dev/pharn@latest init
```

[Explore PHARN](https://github.com/pharn-dev/pharn-oss) · [CLI and installation](https://github.com/pharn-dev/pharn-cli)

### [Argus](https://github.com/pharn-dev/argus) — Understand your Node.js runtime

When a Node.js service slows down, you need useful signals before you need an observability platform.

Argus captures **event loop delay, memory usage, garbage collection, stream backpressure, and HTTP request traces**.

Its zero-external-dependency agent emits NDJSON diagnostics; a collector and live dashboard turn them into time windows, alerts, and request-level visibility.

- **Inspect a running process:** find performance signals and request-level context.
- **Start without an account:** collect data locally and view it in your browser.
- **Integrate when useful:** export metrics and traces through OpenTelemetry.

**Status:** Pre-release. Argus can be built and tried from source; it is not yet published to npm.

[Explore Argus](https://github.com/pharn-dev/argus)

## Ecosystem

- **[pharn-cli](https://github.com/pharn-dev/pharn-cli):** install and update PHARN in existing projects.
- **[skills](https://github.com/pharn-dev/skills):** Claude Code plugin marketplace for working with PHARN Dev tools.

## Our approach

We favor inspectable behavior over black boxes, measured or checkable evidence over unsupported claims, and tools that fit into existing engineering workflows.

## Get involved

Explore the repositories, read their documented limitations, report a concrete issue, or contribute an improvement. Each product's README is the best place to start.