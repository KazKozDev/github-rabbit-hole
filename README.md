<p align="center">
  <img src="./assets/readme-hero.png" alt="README hero banner" width="100%" />
</p>

<h1 align="center">github-rabbit-hole</h1>

<p align="center">
  Research, theory, and practical workflows for writing stronger GitHub READMEs.
</p>

<p align="center">
  <strong>The core idea:</strong> most README “best practices” are not rules.<br />
  They are signals reviewers use under time pressure.
</p>

This repository is for developers who are looking for work and want to understand README best practices from the other side of the table.

The point is not just to collect formatting advice.

It is to understand how GitHub repositories are actually read by:

- recruiters doing first-pass filtering,
- hiring managers deciding whether to keep looking,
- and technical reviewers or team leads who want evidence that a project is real, thoughtful, and competently built.

If you want to know why screenshots, tests, `.env.example`, live demos, commit quality, or project framing matter, this repo is meant to make those signals legible.

## Start Here

| Entry point | Use it for | File |
|---|---|---|
| Research | Full investigation, claim verification, direct quotations, caveats, and references | [`docs/research-report.en.md`](./docs/research-report.en.md) |
| Theory | Shorter explanation of what README signals actually mean and why they matter | [`docs/readme-signals.en.md`](./docs/readme-signals.en.md) |
| Practice | What to show in a demo video and how to present the project clearly | [`docs/video-guide.en.md`](./docs/video-guide.en.md) |
| Coding LLM agent skill | Portable skill for a coding LLM agent that inspects a repo and writes a concise evidence-backed README | [`docs/skill-readme-writer.en.md`](./docs/skill-readme-writer.en.md) |

## Core Idea

This repo is built around one simple idea:

- a README is not decoration,
- most “best practices” are not rules,
- and the strongest improvements come from understanding what a reviewer is inferring from the page.

## Visual Frames

These three visuals summarize the argument:

<p align="center">
  <img src="./assets/evaluation-funnel.png" alt="Evaluation funnel" width="100%" />
</p>

<p><strong>1. A repository is filtered before code is read.</strong></p>

<p align="center">
  <img src="./assets/signal-strength.png" alt="Signal strength" width="100%" />
</p>

<p><strong>2. Not every README signal carries the same weight.</strong></p>

<p align="center">
  <img src="./assets/clone-spectrum.png" alt="Clone spectrum" width="100%" />
</p>

<p><strong>3. The real distinction is endpoint vs. transformation.</strong></p>

## Files

| File | Role |
|---|---|
| [`docs/readme-signals.en.md`](./docs/readme-signals.en.md) | Short practical README guide |
| [`docs/video-guide.en.md`](./docs/video-guide.en.md) | Practical guide for short project demos |
| [`docs/skill-readme-writer.en.md`](./docs/skill-readme-writer.en.md) | Skill for coding LLM agents that write README files from repository evidence |
| [`docs/skill-video-demo.en.md`](./docs/skill-video-demo.en.md) | Skill for coding LLM agents that produce short demo-video workflows |
| [`docs/sources.en.md`](./docs/sources.en.md) | Source index with public links and preserved source names |

## Suggested Path

1. Read the [research report](./docs/research-report.en.md) if you want the evidence.
2. Read the [theory guide](./docs/readme-signals.en.md) if you want the compressed model.
3. Use the [README writer skill](./docs/skill-readme-writer.en.md) if you want a coding LLM agent workflow you can reuse.
