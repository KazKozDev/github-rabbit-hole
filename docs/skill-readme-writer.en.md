---
name: readme-writer
description: Use when the user asks to create, rewrite, improve, audit, or standardize a README for a software repository. Inspect the repository first, extract only defensible facts, and write a concise README that acts as a reviewer-facing landing page rather than a dump of documentation.
input-hint: Repository path and any explicit constraints from the user.
output-hint: A finished README.md draft grounded in repository evidence.
---

# README Writer

## Objective

Write an English `README.md` that helps a reviewer quickly infer:

1. what the project is,
2. whether it is real,
3. whether the author seems competent,
4. and whether the project is worth more attention.

The README is a screening surface, not a place to explain everything.

## Trigger

Use this skill when the user asks to:

- create a README,
- rewrite a README,
- improve or strengthen a README,
- audit a README,
- standardize a project landing page,
- or make a repository more legible for hiring, portfolio, or first-pass review.

## Non-Negotiable Rule

Never write anything that is not supported by repository evidence or explicit user input.

Do not invent:

- positioning,
- performance claims,
- users,
- production status,
- trade-offs,
- architectural intent,
- or roadmap claims.

## Inspection Scope

Inspect enough to answer:

- what the project does,
- why it exists,
- how it is run,
- whether it shows proof of life,
- whether it appears tutorial-shaped or independently developed,
- and whether it shows engineering discipline in setup, tests, CI, and configuration.

Check these when present:

- package manifest or runtime files,
- entry points and major modules,
- deploy configuration,
- `.env.example` or setup samples,
- test configuration,
- CI configuration,
- demo assets,
- existing docs only when they clarify purpose, setup, or architecture.

## Internal Fact Sheet

Before writing, extract:

- project name,
- primary language,
- framework or runtime,
- one-sentence description,
- problem solved,
- likely audience if inferable,
- key capabilities,
- real commands,
- deployment evidence,
- tests present or absent,
- CI present or absent,
- env sample present or absent,
- demo assets,
- evidence of real usage or iteration,
- and unknowns that need user confirmation.

## Writing Strategy

### 1. Optimize for first-screen clarity

The first screen should let the reader answer:

1. What does this project do?
2. Why does it exist?
3. How do I run or try it?

### 2. Prefer strong signals

Strong signals include:

- a clear one-sentence description,
- a live demo, screenshot, or GIF,
- evidence of real deployment or usage,
- tests and CI where relevant,
- setup clarity,
- `.env.example`,
- and a concise reflection on trade-offs or lessons learned.

Weak signals include:

- decorative badges,
- generic marketing language,
- inflated feature lists,
- and over-positioning tutorial-shaped work.

### 3. Context is required

If the repository supports it, explain:

- what problem it solves,
- why it was built,
- what constraints mattered,
- and what changed during implementation.

### 4. Treat clones honestly

If the repository looks tutorial-shaped, do not try to disguise it.

Look for evidence that replication was not the endpoint:

- original logic,
- additional features,
- deployment,
- real usage,
- iteration,
- or visible technical trade-offs.

### 5. Use proof early

If screenshots, GIFs, videos, or live links exist, surface them near the top.

## Recommended Structure

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
12. Trade-offs / lessons learned

## Section Rules

### Title and one-line description

Make them direct and literal.

### Demo block

Place visible proof early when it exists.

### Overview

Keep it short and concrete.

### Features

List only capabilities that map to real code or real flows.

### Setup

Use only real commands.

### Environment variables

Point to `.env.example` if present and document only what is necessary.

### Tests and CI

Surface them briefly when present because they are strong reviewer signals.

### Reflection

Use one concise section such as:

- `Trade-offs`
- `What I Learned`
- `What I’d Do Differently`

## What To Avoid

- unsupported claims,
- hype language,
- decorative filler,
- giant walls of documentation in the main README,
- claiming originality without evidence,
- and generic phrases that could fit any project.

## Output Contract

The final README must:

- feel grounded in repository evidence,
- be readable in one pass,
- make the project feel real and runnable,
- and reduce uncertainty quickly.

If critical facts are missing, return:

- a short note about what is missing,
- and only the minimum questions needed to proceed.
