# Demo Video Guide: What to Show, What to Cut, and Why It Matters

This guide compresses the video-related findings from the research report into one practical document.

Use it when you already have a project and need a short demo that helps a reviewer understand it quickly.

The goal is not to explain everything. The goal is to remove doubt fast:

- the project exists,
- it works,
- it solves a real problem,
- and the author knows what matters about it.

This matters because GitHub repositories are usually filtered before code is read. In the first pass, reviewers look for signs that a project is real, legible, and worth more time. A short demo can help do that if it shows proof quickly.[1][2]

## The main rule

Lead with the result.

The research trail behind this repo repeatedly points in the same direction:

- the first 3 seconds are critical for retention,
- visible proof up front reduces doubt,
- and “proof-first” hooks are stronger than long setup sequences.[1][2]

One of the strongest formulations preserved from the research trail is this:

> “The proof-first hook leads with evidence, results, or credentials before explaining what the video is about. This formula works because it establishes authority and credibility immediately.”

The exact “58% lift” claim that appeared in one secondary source was not treated as cleanly verified from a primary source, but the broader principle still holds: if a viewer does not see the result early, the chances of losing attention rise sharply.[1]

## Recommended length

For most portfolio projects, keep the demo around 20 to 25 seconds.[1]

That is usually enough to show:

- the result,
- one-line context,
- one or two meaningful actions,
- and the result again.

If the project is more complex, extend carefully. If it is simple, do not pad it.

## Recommended structure

### 1. Result first: 0–3 seconds

Show the project already working.

The viewer should immediately see the output, not the setup.

Good openings:

- search already returning results,
- form submission completing successfully,
- chart updating,
- workflow finishing,
- generated output appearing on screen.

Avoid opening with:

- logo animation,
- terminal setup,
- editor tabs,
- folder structure,
- talking head,
- browser tabs that are not the product.

### 2. One-line context: 3–5 seconds

Add one sentence that explains:

- what the project does,
- and what problem it solves.

Example:

> A lightweight budgeting app that helps freelancers track cash flow by client and month.

The sentence should orient the viewer, not oversell the project.

### 3. Core interaction: 5–20 seconds

Show one clear flow.

That usually means:

- one user task,
- one or two actions,
- one visible result.

Do not try to show everything. A short demo is not feature inventory. It is proof that the project works and that the project has a reason to exist.

This is also the section where you can show what makes the project stronger than a tutorial-shaped clone:

- real logic,
- real data,
- real deployment,
- real constraints,
- or evidence of iteration.

### 4. Result again: 20–25 seconds

Close by reinforcing the outcome.

Good endings:

- the result shown again,
- the deployed app visible,
- a realistic task completed,
- one proof point such as real users, activity, or live usage context.

The final image should make the project feel real.

## What to record

Strong footage usually includes:

- the main screen,
- one successful user flow,
- one visible outcome,
- one proof point that the project is real.

Good proof points:

- live deployment,
- realistic data,
- real user interaction,
- nontrivial behavior,
- a workflow that goes beyond a tutorial,
- evidence that the project evolved through feedback or iteration.

## Recording rules

- Record a clean screen, not the whole desktop if it adds noise.
- Increase browser zoom if text is too small.
- Remove unrelated tabs and notifications.
- Keep cursor movement deliberate.
- Avoid tiny interface text that becomes unreadable when embedded.
- Prefer one clean flow over many rushed ones.

## Voiceover and text overlays

You do not always need voiceover.

For README demos, silent screen capture plus short text overlay is often enough.[1]

If you add narration:

- keep it literal,
- explain what is happening,
- do not oversell,
- avoid generic product language.

If you add text overlays, use them only to reduce uncertainty:

- what the project does,
- what the user is seeing,
- why the step matters.

## What weakens a demo

Weak demo patterns include:

- starting with setup instead of the result,
- long intros,
- tiny unreadable interface text,
- too many features in one clip,
- no clear outcome,
- no visible proof that the project is real,
- vanity metrics inside the video.

Stars, downloads, and similar metrics belong next to the video in the README, not inside the clip itself.[1]

## Suggested tools

Practical options preserved from the research:

- Arcade for lightweight browser demo recording,
- QuickTime on macOS for simple capture,
- DaVinci Resolve for free editing,
- ElevenLabs as an optional voiceover tool, though on-screen text is often enough for a 20-second demo.[1]

## Where the video should live

The video should support the README, not live separately from it.

Best placement:

- embed a GIF directly in the README,
- or link to a hosted video,
- or link to YouTube if needed.[1]

The README is still the main surface. The video helps it carry proof faster.

## Practical checklist

- [ ] The first frame shows the project, not the tooling around it
- [ ] The result is visible in the first 3 seconds
- [ ] The problem statement fits in one sentence
- [ ] The clip stays around 20–25 seconds unless complexity justifies more
- [ ] Only one clear flow is shown
- [ ] The interface is readable at embed size
- [ ] The ending reinforces that the project is real
- [ ] The video is embedded in the README or linked next to the demo section

## Read next

- [Full research report](./research-report.en.md)
- [README signals guide](./readme-signals.en.md)

## References

[1]: ./research-report.en.md
[2]: https://dev.to/jsgurujobs/optimizing-your-github-profile-for-job-hunting-a-technical-guide-578j
