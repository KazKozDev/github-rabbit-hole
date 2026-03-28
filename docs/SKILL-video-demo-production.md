---
name: video-demo-production
description: Produce a short proof-first demo-video plan for a software project. Use when the user wants a project walkthrough, README GIF/video plan, or a repeatable agent workflow for showing a project clearly under limited reviewer attention. The output must be grounded in repository evidence and optimized for first-pass clarity.
input-hint: Repository path plus any available demo assets.
output-hint: Demo-video plan, script, or concise asset checklist.
---

# Demo Video Skill, Production Ready

## Objective

Generate a short demo-video plan that helps a reviewer answer:

1. Is the project real?
2. What does it do?
3. What is the main interaction?
4. Why is it worth more attention?

The video is a proof asset, not a feature dump.

## Trigger

Use this skill when the user asks to:

- create a demo video
- plan a project walkthrough
- make a README GIF/video
- improve an existing project demo
- standardize a short proof-first project presentation

## Non-Negotiable Rules

- Lead with the result, not the setup.
- Show one flow, not everything.
- Never invent proof points.
- Do not claim users, deployment, or impact without evidence.
- Prefer a short clear demo over a long unfocused one.

## Inputs

Minimum useful inputs:

- repository contents
- screenshots or recordings if available
- live deployment if available
- one-line project description
- strongest user flow
- realistic demo data if available

## Inspection Scope

Inspect enough to answer:

- what visible result is strongest
- what user flow is clearest
- what can be shown without setup-heavy explanation
- what makes the project look real rather than tutorial-shaped

Look for:

- live deployment links
- screenshot assets
- GIFs or previous videos
- README demo sections
- realistic demo data
- features that visibly prove value

## Strategy

Optimize for:

- proof in the first frame
- one clear flow
- readability at small embed size
- minimal dead time
- closing on a reinforced result

Research-aligned defaults:

- first 3 seconds matter most
- proof-first beats setup-first
- 20–25 seconds is a strong default range
- the video should strengthen the README, not replace it

## Recommended Sequence

### 1. Result first: 0–3 seconds

- show the project already working
- show the visible output immediately

### 2. One-line context: 3–5 seconds

- explain what the project does
- explain the problem it solves

### 3. Core interaction: 5–20 seconds

- one user task
- one or two meaningful actions
- one visible result

### 4. Result again: 20–25 seconds

- reinforce the output
- close on proof

## Recording Rules

- avoid noisy desktop capture
- zoom small UI if needed
- remove unrelated tabs and notifications
- keep cursor movement deliberate
- avoid unreadable text

## What To Avoid

- opening with setup
- logo animation
- editor tabs
- long intros
- too many features
- no visible outcome
- vanity metrics inside the video

## Placement Rules

The video should support the README.

Best placements:

- embedded GIF in the README
- hosted video linked from the README
- YouTube link if necessary

## Output Contract

The final output must include:

- the strongest flow to show
- a short sequence plan
- proof points to surface
- what to cut
- where the video should live

If the repository has no clear visual result, say so and explain what additional input or assets are needed.

## Related Files

- [Canonical video skill notes](./skill-video-demo.en.md)
- [Video guide](./video-guide.en.md)
- [Research report](./research-report.en.md)
