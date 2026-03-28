# Agent Skill: README Writer

This is a portable GitHub-friendly version of the README-writing agent skill used in the workflow behind this repository.

Its purpose is simple:

Write English `README.md` files as concise project entry points grounded in repository evidence.

## What the agent should optimize for

Within 10 to 20 seconds, a reader should be able to answer:

1. What does this project do?
2. Why does it matter?
3. How do I run or try it?

The README should feel like a landing page plus technical overview, not like unstructured documentation.

## Core rule

Never write anything that is not supported by repository evidence or explicit user input.

## Input

The agent should inspect the repository before writing.

Minimum useful evidence:

- package manifest or runtime file,
- deployment config if present,
- `.env.example` or setup samples,
- test configuration,
- entry points,
- major modules,
- any existing docs that clarify purpose or setup.

## Internal fact sheet

Before writing, the agent should extract:

- project name,
- primary language,
- framework or runtime,
- one-sentence description,
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
- unknowns that require explicit user input.

## Writing strategy

The README should:

- prioritize first-screen clarity,
- avoid hype,
- use only defensible claims,
- keep commands real,
- stay concise,
- and explain why the project exists, not just what stack it uses.

## Recommended structure

1. Title + one-line description
2. Highlights
3. Demo or screenshot if it exists
4. Overview
5. Features
6. Architecture if the project is complex enough
7. Setup / installation
8. Usage
9. Environment variables
10. Tests
11. Trade-offs, lessons, or what changed

## What the agent should avoid

- invented positioning,
- unsupported performance claims,
- decorative badges,
- empty sections,
- generic phrases like “modern solution” or “powerful platform,”
- turning the README into full documentation.

## What makes the output stronger

The strongest README outputs usually include:

- one sentence that clearly states what the project does,
- visible proof that it works,
- setup clarity,
- real commands,
- and one small section showing reflection or engineering judgment.

## Expected output standard

The final README should make the project feel:

- real,
- readable,
- runnable,
- and more examined than assembled.

## Related files

- [Full research report](./github-profile-hiring-guide.en.md)
- [README signals short guide](./readme-signals-short-guide.en.md)
- [Demo video guide](./video-demo-guide.en.md)
