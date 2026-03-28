# Agent Skill for Coding LLM Agents: Demo Video Producer

This is the canonical GitHub-friendly video skill for this repository.

It merges the original demo-video workflow with the research findings behind first-pass reviewer attention, proof-first presentation, and short demo structure.

## Purpose

Help a coding LLM agent produce a short project demo that shows the result first and explains the project with minimal friction.

The goal is not a flashy clip.

The goal is a demo that helps a reviewer quickly infer:

1. the project is real,
2. it works,
3. the main interaction is understandable,
4. and the project is worth more attention.

## Core rule

Lead with the result, not with setup.

## What the agent should optimize for

The video should reduce doubt fast.

It should make the viewer feel:

- this exists,
- this works,
- I understand what it is,
- and I should keep looking.

## Input

The agent should gather:

- screenshots or screen recordings,
- project title,
- one-sentence problem statement,
- key flow to demonstrate,
- proof that the project is real,
- target platform if known.

## Recommended workflow

### 1. Select the right flow

Choose one user flow only.

Prefer:

- the primary action,
- a meaningful before/after state,
- or the feature that most clearly separates the project from tutorial-shaped work.

### 2. Gather assets

Useful assets:

- screenshots,
- screen recordings,
- UI states,
- short text overlays,
- deployment link or usage proof,
- optional narration.

### 3. Build the sequence

Recommended sequence:

1. Result on screen immediately
2. One-line context
3. Core interaction
4. Close with proof or outcome

### 4. Keep the pace tight

For README demos and portfolio clips:

- target about 20 to 25 seconds,
- cut dead time,
- keep the UI readable,
- avoid trying to show everything.

### 5. Render cleanly

The final output should:

- be readable at small size,
- avoid unnecessary transitions,
- use text sparingly,
- and end on a frame that reinforces the project’s value.

## Research-backed heuristics

### 1. The first 3 seconds matter most

The viewer should see the result immediately.

Do not open with:

- setup,
- terminal commands,
- editor tabs,
- folder structure,
- logo animation,
- or a talking head.

Open with:

- the app already running,
- the key action already in motion,
- or the output clearly visible.

### 2. Proof beats explanation

A short demo works when it establishes confidence before context.

The sequence should make the viewer think:

- this is real,
- this works,
- I understand what it is.

### 3. Show one flow, not everything

A good demo is not feature inventory.

Choose one flow that best proves:

- value,
- clarity,
- realness,
- and independent judgment.

### 4. Use visible proof points

If available, include:

- live deployment,
- realistic data,
- real user interaction,
- nontrivial behavior,
- evidence of iteration,
- visible constraints or trade-offs.

## Good overlays

Use overlays only when they reduce uncertainty.

Good overlay examples:

- what the project does,
- what the user is seeing,
- what changed,
- why this flow matters.

## Recording rules

- record a clean screen, not a noisy desktop
- zoom the interface if text is small
- remove unrelated tabs and notifications
- keep cursor movement deliberate
- avoid unreadable UI text
- prefer one clean flow over many rushed ones

## What the agent should avoid

- opening with setup or code editor,
- long intros,
- unreadable text,
- too many features in one clip,
- empty motion with no outcome,
- marketing voice with no visible proof,
- vanity metrics inside the video.

## Tooling notes

This workflow was originally based on a Remotion-driven video production skill for programmatic walkthroughs, but the logic also works for simple screen recordings edited manually.

If automation is available, the agent can:

- gather images or screen captures,
- assemble a short sequence,
- add text overlays,
- and render an exportable video file.

Practical tools preserved from the research trail:

- Arcade
- QuickTime
- DaVinci Resolve
- ElevenLabs for optional voiceover support

## Placement

The video should support the README, not live separately from it.

Best placement:

- embed a GIF directly in the README,
- or link to a hosted video,
- or link to YouTube if needed.

## Success criteria

A good demo video:

- shows the project working immediately,
- keeps the viewer oriented,
- highlights only the most important flow,
- and makes the project feel real.

## Related files

- [Demo video guide](./video-guide.en.md)
- [Full research report](./research-report.en.md)
- [README writer agent skill](./skill-readme-writer.en.md)
