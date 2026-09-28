# Agent Builder

A security-first, portable framework that helps nontechnical users design, create, and evolve AI agents using any capable LLM and editable workspace.

## Start

Give a capable LLM this instruction:

`use github.com/mjcdata/agent-builder/AGENTS.md`

Agent Builder will guide you through defining the agent you want, choosing an editable workspace the LLM can actually maintain, creating the minimum necessary instructions and agents, and testing the result.

## Explain it first

If you want to understand the framework before using it, ask:

`explain github.com/mjcdata/agent-builder/AGENTS.md`

## Design philosophy

Agent Builder is:

- **Security first** — security outranks convenience, autonomy, and speed.
- **Portable by default** — it avoids unnecessary dependence on a particular LLM, vendor, or workspace.
- **Nontechnical first** — describe what you want; the Advisor handles the framework details.
- **Minimal by default** — agents, files, folders, and processes are added only when they solve a real problem.
- **Self-maintaining** — agents are designed to proactively keep their editable instructions and documentation aligned with durable user decisions.

GitHub is a useful reference workspace, but it is not required. The framework can be used with another durable workspace when the chosen LLM can safely read and edit it.

## Repository structure

This repository intentionally starts small:

- `README.md` — explains Agent Builder to people.
- `AGENTS.md` — contains the portable operating framework for LLMs.

More files or folders should be added only when the project grows enough to need them.
