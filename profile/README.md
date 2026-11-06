# PHARN Dev

**Know if an agent's PR is safe to merge.**

We build the floor for AI-assisted development. The main product is **pharn-ci** — one CI check that tells a team whether an agent's pull request is safe to merge.

## Main product

### [pharn-ci](https://github.com/pharn-dev/pharn-ci) — One CI check for agent PRs

Agents write diffs faster than people can review them. pharn-ci runs on every pull request and answers the cheap, mechanical questions before a human opens it:

- Did the tests actually execute the new code? (diff coverage)
- Does the repository tell agents how to work in it? (agent setup inventory)
- Did someone skip, delete, or weaken tests? (test integrity)

One GitHub Action. One PR comment. One status check. AI-agnostic. Deterministic. Source code never leaves your CI.

```yaml
- uses: pharn-dev/pharn-ci@v0
```

[pharn-ci](https://github.com/pharn-dev/pharn-ci) · [pharn.dev](https://pharn.dev)

## Open-source methodology

### [PHARN](https://github.com/pharn-dev/pharn-oss) — Ship features right with AI agents

The open-source methodology that keeps the reasoning next to the code. Spec, plan, and checks stay in Git, so months later you can still answer what was asked, what was checked, and what was only the model's opinion.

```bash
npx @pharn-dev/pharn@latest init
```

[pharn-oss](https://github.com/pharn-dev/pharn-oss) · [pharn-cli](https://github.com/pharn-dev/pharn-cli)

## Runtime diagnostics

### [Phargus](https://github.com/pharn-dev/phargus) — See what's running in your Node.js app

Lightweight, zero-dependency runtime diagnostics for Node.js. Event loop lag, memory, GC, HTTP requests, and stream backpressure. No account required.

[Explore Phargus](https://github.com/pharn-dev/phargus)

## Ecosystem

- **[skills](https://github.com/pharn-dev/skills):** Claude Code skills for Pharn and Phargus.
- **[pharn-cli](https://github.com/pharn-dev/pharn-cli):** Install and update PHARN in existing projects.

## Our approach

We favor behavior you can read over black boxes, claims you can check over claims you have to trust, and tools that fit the workflow you already have. The floor is only as strong as the cases it refuses to guess on.

## Get involved

Explore the repositories, read their documented limitations, report a concrete issue, or contribute an improvement. Each product's README is the best place to start.
