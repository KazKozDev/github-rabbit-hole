# Agent Skill: Demo Video Producer

This is a portable GitHub-friendly version of the demo-video workflow used for agent-assisted project walkthroughs.

Its job is to help an agent produce a short project demo that shows the result first and explains the project with minimal friction.

## What the agent should optimize for

The video should help a reviewer answer:

1. Is the project real?
2. What does it do?
3. What is the main interaction?
4. Why is it worth more attention?

## Core rule

Lead with the result, not with setup.

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

- target 20 to 30 seconds,
- cut dead time,
- keep the UI readable,
- avoid trying to show everything.

### 5. Render cleanly

The final output should:

- be readable at small size,
- avoid unnecessary transitions,
- use text sparingly,
- and end on a frame that reinforces the project’s value.

## What the agent should avoid

- opening with setup or code editor,
- long intros,
- unreadable text,
- too many features in one clip,
- empty motion with no outcome,
- marketing voice with no visible proof.

## Good overlays

Use overlays only when they reduce uncertainty.

Good overlay examples:

- what the project does,
- what the user is seeing,
- what changed,
- why this flow matters.

## Tooling notes

This workflow was originally based on a Remotion-driven video production skill for programmatic walkthroughs, but the logic also works for simple screen recordings edited manually.

If automation is available, the agent can:

- gather images or screen captures,
- assemble a short sequence,
- add text overlays,
- and render an exportable video file.

## Success criteria

A good demo video:

- shows the project working immediately,
- keeps the viewer oriented,
- highlights only the most important flow,
- and makes the project feel real.

## Related files

- [Demo video guide](./video-demo-guide.en.md)
- [Full research report](./github-profile-hiring-guide.en.md)
- [README writer agent skill](./readme-writer-agent-skill.en.md)
