---
name: readme-generator-research-aligned
description: Write or rewrite English README.md files for software repositories as concise project entry points grounded in repository evidence and aligned with hiring-oriented README research. Use when the user asks to create, improve, audit, or standardize a README and wants the result optimized for first-pass reviewer attention, signal clarity, and practical credibility rather than generic documentation style.
---

# README Generator, Research Aligned

README is not only documentation. It is also part of the screening surface of a project.

Treat the first screen like a landing page plus technical overview. The README should help a reviewer quickly infer:

- what the project is,
- whether it is real,
- whether the author seems competent,
- and whether the project is worth more attention.

This skill is aligned to the research in this repository:

- repositories are filtered before code is read,
- not every signal carries the same weight,
- context matters,
- tutorial-shaped clones are weak when replication is the endpoint,
- and visible proof reduces doubt faster than abstract explanation.

**Golden rule: never write anything that is not supported by repository evidence or explicit user input.**

**Language: write the README in English unless the user explicitly asks for another language.**

## Workflow

1. Inspect the repository before writing.
2. Extract only defensible facts.
3. Identify the strongest signals the repository already contains.
4. Build the README in an order that optimizes first-screen clarity.
5. Keep the main file concise and move depth to `docs/` only when needed.
6. Ask the user only when a missing fact materially changes correctness.
7. Check whether the first screen reduces uncertainty quickly.

## Inspect The Repository

Read the minimum set of files needed to understand the project.

Check these if they exist:

- `package.json`, `pyproject.toml`, `requirements.txt`, `Cargo.toml`, `go.mod`, `pom.xml`, or equivalent
- `Makefile`, `Dockerfile`, `docker-compose.yml`
- `.env.example`, `.env.sample`
- deploy config such as `vercel.json`, `netlify.toml`, `fly.toml`, `render.yaml`, `Procfile`
- `README.md`, `CONTRIBUTING.md`, `LICENSE`, `.github/`
- entry points, routing files, main modules, public exports
- test configuration and common commands
- demo assets such as screenshots, GIFs, or hosted links
- `docs/` files only if they clarify setup, positioning, architecture, or usage

Inspect structure to about 2 levels deep and read only the key source files needed to answer:

- what the project does
- why it exists
- who it is for, if inferable
- whether it looks tutorial-shaped or independently developed
- whether it has visible proof of life
- whether it shows discipline in setup, testing, and configuration
- real setup and usage commands
- architectural components worth naming
- current status, if explicitly evident

Build an internal facts sheet before writing:

```text
Project name:
Primary language:
Framework/runtime:
What it does in one sentence:
Problem it solves:
Audience:
Key capabilities:
Entry point:
Core modules:
Real commands:
Has tests:
Has CI/CD:
Has deployment:
Has demo assets:
Has .env example:
Has docs:
Has evidence of real usage or iteration:
Signals of independent judgment:
License:
Unknowns that require user input:
```

If you cannot determine what the project does after reading the code, ask the user. Do not guess.

## Writing Strategy

Write the README as a concise, scan-friendly project entry point.

Priorities:

- clarity in the first screen
- repository-backed claims only
- real commands only
- proof before explanation where possible
- strong signals over decorative details
- context over generic feature lists
- execution quality over hype
- structure adapted to the project type

Default length targets:

- 300-500 words for a simple script or small CLI
- 500-800 words for a typical app, library, or service
- up to about 1200 words only for genuinely complex systems

If the README starts turning into documentation, cut detail and move depth to `docs/`.

## Research-Aligned Heuristics

### 1. Optimize for first-pass reading

Within 10-20 seconds, the reader should be able to answer:

- What does this project do?
- Why does it exist?
- How do I run or try it?

The first screen should do more work than the rest of the file.

### 2. Prefer strong signals

When supported by the repository, these signals are high-value:

- a clear one-sentence project description
- a live demo, screenshot, or GIF
- some evidence of real deployment or real users
- tests and CI
- setup clarity
- `.env.example`
- meaningful commit patterns, if visible in repo context
- one section showing reflection, trade-offs, or lessons learned

Low-value or weak signals:

- decorative badges
- generic marketing language
- empty “feature inflation”
- tutorial-shaped repos with no visible original logic
- README copy that sounds assembled rather than examined

### 3. Context is not optional

A project should not read like:

> here is a todo app

It should explain:

- what problem it solves
- why it was built
- what constraints shaped it
- what was difficult
- what changed during implementation

### 4. Treat clones carefully

If the repository looks like a recognizable tutorial clone, do not try to hide that by marketing language.

Look for evidence that replication was not the endpoint:

- original logic
- additional features
- deployment
- real users
- iteration
- explicit technical trade-offs

If that evidence is absent, stay factual and modest.

### 5. Use visible proof when it exists

If the repository has a live demo, screenshot, GIF, or short video, surface it early.

Visible proof reduces doubt faster than abstract explanation.

## Recommended Structure

Use this order when the repository supports it. Include the sections that are useful and supported by evidence. Do not force empty or speculative sections.

### 1. Title + Tagline

Always include.

```md
# Project Name

One-line description of what the project does.
```

Rules:

- one line
- direct and specific
- avoid generic phrases like "modern solution" or "powerful platform"
- prefer concrete formulations such as "Browser extension for capturing and summarizing support conversations"

### 2. Demo

Include early if a real asset or live URL exists.

Use:

- GIF
- screenshot
- short video
- live deployment link

If none exists, omit the section rather than inventing a placeholder.

### 3. Overview

Explain:

- what the project does
- who it is for, if inferable
- why it exists

Rules:

- 3-6 short lines
- about 120 words max
- no filler or marketing copy

### 4. Problem / Context

Include when there is evidence for it.

This section is often what prevents the project from reading like a tutorial wrapper.

Useful context includes:

- what was frustrating or missing
- why the project was built
- what constraints shaped it
- what kind of iteration or usage it saw

### 5. Features

Rules:

- 4-10 items max
- each item must map to real code, real outputs, or real user flows
- keep wording short and factual

### 6. Architecture

Include when the project has meaningful internal structure.

Keep it lightweight:

- major components
- responsibilities
- one short diagram if it genuinely helps

### 7. Setup / Installation

Use only real commands.

If environment variables are required, point clearly to `.env.example` if present.

### 8. Usage

Show the shortest path to a successful run or interaction.

### 9. Environment Variables

Include only when necessary and backed by repository evidence.

### 10. Tests / CI

If tests or CI exist, surface that briefly. These are strong signals of engineering discipline.

### 11. Reflection Section

Prefer one concise reflective section:

- `What I Learned`
- `Trade-offs`
- `What I’d Do Differently`

This is one of the strongest ways to signal judgment rather than assembly.

## What To Avoid

- invented positioning
- unsupported performance claims
- decorative badges as filler
- empty sections
- walls of hype
- generic phrases like “cutting-edge” or “powerful solution”
- pretending a tutorial clone is original without evidence
- turning the README into full documentation

## Output Standard

The final README should make the project feel:

- real
- legible
- runnable
- and more examined than assembled

If the file succeeds, a reviewer should feel that the author understands both the project and the reader’s limited attention.

## Related Files

- [Research report](./research-report.en.md)
- [README signals guide](./readme-signals.en.md)
- [Canonical README skill notes](./skill-readme-writer.en.md)
