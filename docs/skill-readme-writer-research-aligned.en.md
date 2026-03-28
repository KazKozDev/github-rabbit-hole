# Agent Skill for Coding LLM Agents: README Writer, Aligned to the Research

This file is a research-aligned version of the README-writing skill.

It keeps the original purpose of the skill, but tightens it using the conclusions from the repository’s research report:

- a README is part of first-pass screening, not just documentation,
- not every signal carries the same weight,
- context matters,
- tutorial-shaped clones are weak when replication is the endpoint,
- and visible proof often matters before code is ever read.[1]

## Purpose

Write English `README.md` files as concise project entry points grounded in repository evidence.

The target is not “a nice README.”

The target is a README that helps a reviewer quickly infer:

1. what the project is,
2. whether it is real,
3. whether the author seems competent,
4. and whether the project is worth more attention.[1]

## Core framing

Treat the README as a screening surface.

The first job of the file is not completeness. Its first job is to survive the first pass, reduce uncertainty, and justify continued attention.[1]

That means the agent should optimize for:

- clarity in the first screen,
- proof before explanation where possible,
- strong signals over decorative details,
- context over generic feature lists,
- and only defensible claims.

## Non-negotiable rule

Never write anything that is not supported by repository evidence or explicit user input.

Do not invent:

- positioning,
- performance claims,
- users,
- production status,
- trade-offs,
- or architectural intent.

## What the agent should inspect

Minimum useful evidence:

- package manifest or runtime file,
- deployment config if present,
- `.env.example` or setup samples,
- test configuration,
- CI configuration,
- entry points,
- major modules,
- demo assets,
- existing docs that clarify purpose, setup, or architecture.

The agent should inspect enough to answer:

- what the project does,
- why it exists,
- whether it appears tutorial-shaped or independently developed,
- whether it has visible proof of life,
- whether it shows discipline in setup, testing, and configuration.[1][2][5]

## Internal fact sheet

Before writing, extract:

- project name,
- primary language,
- framework or runtime,
- one-sentence project description,
- problem solved,
- likely audience if inferable,
- key capabilities,
- entry point,
- core modules,
- real commands,
- tests present or absent,
- CI present or absent,
- deployment evidence,
- demo assets,
- env sample,
- evidence of real usage or iteration,
- signals that suggest independent judgment,
- unknowns that require explicit user input.

## Research-backed writing strategy

### 1. Optimize for first-screen clarity

Within 10 to 20 seconds, the reader should be able to answer:

1. What does this project do?
2. Why does it exist?
3. How do I run or try it?

The first screen should do more work than the rest of the file.[1]

### 2. Prefer strong signals

Research-backed strong signals include:

- a clear one-sentence description,
- a live demo, screenshot, or GIF,
- some evidence of real users or real deployment,
- tests and CI where relevant,
- setup clarity,
- `.env.example`,
- meaningful commit history,
- a section that shows reflection, trade-offs, or lessons learned.[1][2][5]

Weak or low-value signals include:

- decorative badges,
- generic marketing language,
- empty feature inflation,
- tutorial-shaped projects with no original logic,
- README copy that sounds assembled rather than examined.[1][2]

### 3. Context is not optional

A project should not read like:

> here is a todo app

It should explain:

- what problem it solves,
- why it was built,
- what constraints mattered,
- what was difficult,
- and what changed through implementation.[2]

### 4. Treat clones carefully

If the repository looks like a recognizable tutorial clone, the README should not try to hide that.

Instead, the agent should look for evidence that replication was not the endpoint:

- original logic,
- additional features,
- deployment,
- real users,
- real iteration,
- or technical trade-offs.[2][3]

If no such evidence exists, the README should stay factual and avoid over-positioning the project.

### 5. Use proof where it exists

If the repo has a live demo, screenshot, GIF, or short video, surface it early.

Visible proof reduces doubt faster than abstract explanation.[1][2]

## Recommended structure

Use this order when the repository supports it:

1. Title
2. One-line description
3. Demo / screenshot / GIF / live link
4. Overview
5. Problem / context
6. Features
7. Architecture if warranted
8. Setup / installation
9. Usage
10. Environment variables
11. Tests / CI
12. What I learned / trade-offs / what I’d do differently

## Section guidance

### Title + one-line description

Make it direct and literal.

Bad:

- “A modern platform for seamless productivity”

Better:

- “Browser extension for capturing and summarizing support conversations”

### Demo

If a live demo, screenshot, GIF, or video exists, put it early.

The README should not make the reader imagine whether the project works.[1]

### Overview

Keep this short.

It should explain:

- what the project does,
- who it is for if inferable,
- and why it exists.

### Problem / context

This is where the file can stop sounding like a tutorial wrapper.

Useful context includes:

- what was frustrating or missing,
- why the project was built,
- what constraints shaped it,
- what kind of usage or iteration it saw.[2]

### Features

List only features that map to real code, real flows, or visible outputs.

Do not pad.

### Setup / installation

Use only real commands.

If the project requires environment variables, document them clearly and point to `.env.example` if it exists.[5]

### Tests / CI

If the repo contains tests or CI, surface that briefly because it is a strong signal of engineering discipline.[1][3][5]

### Reflection section

Prefer one concise reflective section:

- `What I Learned`
- `Trade-offs`
- `What I’d Do Differently`

This is one of the strongest ways to signal judgment rather than assembly.[2]

## What the agent should avoid

- invented positioning,
- unsupported claims,
- decorative badges as filler,
- walls of hype,
- generic phrases like “cutting-edge” or “powerful solution,”
- pretending a tutorial clone is original without evidence,
- turning the README into full documentation.

## Output standard

The final README should make the project feel:

- real,
- legible,
- runnable,
- and more examined than assembled.

If the file succeeds, a reviewer should feel that the author understands both the project and the reader’s limited attention.

## Related files

- [Research report](./research-report.en.md)
- [README signals guide](./readme-signals.en.md)
- [Video guide](./video-guide.en.md)

## References

[1]: ./research-report.en.md
[2]: https://dev.to/__be2942592/how-to-build-a-developer-portfolio-that-actually-gets-you-hired-2026-6kn
[3]: https://www.reddit.com/r/learnprogramming/comments/15l8gur
[5]: https://onenine.com/best-practices-for-environment-specific-configurations/
