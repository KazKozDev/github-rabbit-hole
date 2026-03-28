---
name: readme-generator-research-aligned
description: Produce or rewrite an English README.md for a software repository as a reviewer-facing project entry point. Use when the user asks to create, improve, rewrite, audit, standardize, strengthen, or review a README, especially for GitHub projects, hiring visibility, portfolio polish, open-source presentation, or first-pass reviewer clarity. The output must be grounded in repository evidence and optimized for signal clarity rather than generic documentation style.
---

# README Generator, Production Ready

## Objective

Generate an English `README.md` that helps a time-constrained reviewer answer:

1. What does this project do?
2. Why does it matter?
3. Is it real?
4. How do I run or try it?

The README is a project entry point, not full documentation.

## Trigger

Use this skill when the user asks to:

- create a README
- rewrite a README
- improve a README
- standardize a README
- audit whether a README is strong enough for hiring, open source, or product-facing review

## Non-Negotiable Rules

- Never invent facts.
- Never claim users, production status, metrics, or performance without evidence.
- Never describe a tutorial-shaped project as original without repository support.
- Use English unless the user explicitly asks for another language.
- Prefer omission over speculation.

## Inputs

Minimum useful inputs:

- repository files
- package/runtime metadata
- setup commands
- deployment evidence if present
- test/CI evidence if present
- screenshot/demo assets if present
- explicit user context if the repo alone is insufficient

## Inspection Scope

Inspect the minimum set of files needed to build a defensible README:

- package manifest or runtime file
- `README.md`, if one already exists
- deploy config
- `.env.example` or equivalent
- tests and CI config
- entry points
- main modules
- `docs/` only when needed for setup, architecture, or positioning

Build an internal facts sheet:

```text
Project name:
Primary language:
Framework/runtime:
One-line description:
Problem solved:
Audience:
Key capabilities:
Entry point:
Real commands:
Has tests:
Has CI:
Has deployment:
Has demo assets:
Has env sample:
Has evidence of real usage:
Signals of independent judgment:
Unknowns:
```

If the core purpose of the project is unclear after inspection, stop and ask for clarification.

## Strategy

Optimize for:

- first-screen clarity
- defensible claims only
- proof before explanation where possible
- strong signals over decorative details
- context over generic feature lists
- concise structure

Research-aligned priorities:

- a clear one-sentence description
- visible proof if available
- setup clarity
- tests / CI when present
- `.env.example` when present
- one section that shows reflection, trade-offs, or lessons learned

## Recommended Output Structure

Use this order when supported by evidence:

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
12. Reflection section

## Section Rules

### Title + one-line description

- one line
- direct and specific
- no hype

### Demo

- include only if a real asset or live link exists
- surface early

### Overview

- explain what the project does
- explain why it exists
- explain who it is for if inferable

### Problem / context

Use when supported by repo evidence or user input.

### Features

- list only real capabilities
- no padding

### Setup / installation

- real commands only
- point to `.env.example` if relevant

### Tests / CI

- mention briefly if present
- do not invent them if absent

### Reflection section

Prefer one concise section such as:

- `What I Learned`
- `Trade-offs`
- `What I’d Do Differently`

## Failure Modes To Avoid

- generic startup copy
- decorative badges as filler
- unsupported performance language
- inflated originality claims
- README as documentation dump
- walls of text before the reader understands the project

## Output Contract

The final output must:

- be readable in one pass
- feel grounded in repository evidence
- make the project feel real, runnable, and examined
- avoid speculation

If critical facts are missing, return:

- a short explanation of what is missing
- the minimum questions needed to proceed
