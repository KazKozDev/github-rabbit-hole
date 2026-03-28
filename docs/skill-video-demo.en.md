---
name: demo-planner
description: Use when the user asks to create, improve, script, structure, or review a project demo video, walkthrough clip, README GIF, or short product recording. Build a short proof-first demo plan grounded in repository evidence and optimized for first-pass reviewer clarity.
input-hint: Repository path plus any screenshots, recordings, live links, or demo constraints.
output-hint: A finished short demo-video plan, script, or shot list.
---

# Demo Planner

## Objective

Produce a short demo plan that helps a reviewer answer:

1. Is the project real?
2. What does it do?
3. What is the main interaction?
4. Why is it worth more attention?

The demo is a proof asset, not a feature dump.

## Trigger

Use this skill when the user asks to:

- create a demo video,
- plan a walkthrough,
- make a README GIF,
- improve an existing demo,
- script a short product recording,
- or structure a proof-first showcase for a repository.

## Non-Negotiable Rules

- Lead with the result, not the setup.
- Show one flow, not everything.
- Never invent proof points.
- Do not claim users, deployment, or impact without evidence.
- Prefer one short clear demo over a long unfocused one.

## Inspection Scope

Inspect enough to answer:

- what visible result is strongest,
- what user flow is clearest,
- what can be shown without setup-heavy explanation,
- and what makes the project feel real rather than tutorial-shaped.

Look for:

- live deployment links,
- screenshot or recording assets,
- README demo sections,
- realistic demo data,
- and features that visibly prove value.

## Inputs

Minimum useful inputs:

- repository contents,
- screenshots or recordings if available,
- live deployment if available,
- one-line project description,
- strongest user flow,
- and realistic demo data if available.

## Strategy

Optimize for:

- proof in the first frame,
- one clear flow,
- readability at small embed size,
- minimal dead time,
- and a closing frame that reinforces the result.

Defaults:

- the first 3 seconds matter most,
- proof-first beats setup-first,
- 20 to 25 seconds is a strong default range,
- and the demo should strengthen the README, not replace it.

## Recommended Sequence

### 1. Result first: 0 to 3 seconds

- show the project already working,
- show the visible output immediately.

### 2. One-line context: 3 to 5 seconds

- explain what the project does,
- explain the problem it solves.

### 3. Core interaction: 5 to 20 seconds

- one user task,
- one or two meaningful actions,
- one visible result.

### 4. Result again: 20 to 25 seconds

- reinforce the outcome,
- close on proof.

## Overlay Rules

Use text only when it reduces uncertainty.

Good overlay roles:

- what the project does,
- what the viewer is seeing,
- what changed,
- why the shown flow matters.

## Recording Rules

- record a clean screen,
- remove unrelated tabs and notifications,
- zoom small UI if needed,
- keep cursor movement deliberate,
- avoid unreadable text,
- and prefer one clean flow over many rushed ones.

## What To Avoid

- opening with setup,
- terminal commands,
- editor tabs,
- logo animation,
- long intros,
- too many features,
- no visible outcome,
- and marketing copy with no proof.

## Tooling

Use any toolchain that can produce a short clean demo.

Common options:

- QuickTime,
- Arcade,
- DaVinci Resolve,
- Remotion,
- ElevenLabs for optional voiceover.

## Placement Rules

The demo should support the README.

Preferred placement:

- embedded GIF in the README,
- hosted video linked from the README,
- or YouTube link if necessary.

## Output Contract

The final output must include:

- the strongest flow to show,
- a short sequence plan,
- proof points to surface,
- what to cut,
- and where the demo should live.

If the repository has no clear visual result, say so and explain what assets or input are missing.
