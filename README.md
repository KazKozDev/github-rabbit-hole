# github-rabbit-hole

An evidence-backed research repository on how GitHub profiles are evaluated in hiring, what separates real projects from tutorial-shaped work, how README structure affects first-pass screening, and how GitHub + Medium + LinkedIn reinforce each other.

This repo contains an English GitHub-friendly version of a source-backed verification report and turns it into something easier to browse, cite, and reuse.

## Start here

- [`docs/github-profile-hiring-guide.en.md`](./docs/github-profile-hiring-guide.en.md)  
  Full report in English:
  - claim verification,
  - source-backed caveats,
  - practical implementation steps,
  - final checklists,
  - section on what was inaccurate or overstated.

- [`docs/readme-signals-short-guide.en.md`](./docs/readme-signals-short-guide.en.md)  
  Short practical version:
  - strongest README signals,
  - weak signals,
  - clone rule,
  - practical minimum to fix first.

## Why this repo exists

There is a lot of GitHub portfolio advice online, but much of it is repeated as ritual:

- “add a GIF,”
- “show tests,”
- “delete clones,”
- “write a blog,”
- “make your profile look professional.”

Some of that advice is useful. Some of it is overstated. Very little of it is traced carefully back to source material.

This repository exists to do exactly that:

- verify the common claims,
- preserve the nuance,
- and turn the results into something practical.

## Core conclusions

The strongest conclusions from the report are:

1. A GitHub repository is usually not evaluated code-first. It is filtered through signals first.
2. A README is not decoration. It is part of the screening surface.
3. Tests, CI, `.env.example`, setup clarity, and meaningful commits matter because they compress information about how you work.
4. Raw clones are weak signals when replication is the endpoint. Extended projects, real users, and clear trade-offs change that interpretation.
5. Medium articles help most when they extend real project work, not when they replace it.

In short:

> Most GitHub “best practices” are not universal standards. They are compressed signals under time pressure.

## What you can use this for

Use this repo if you want to:

- clean up your GitHub profile for hiring,
- make your README more convincing,
- distinguish real portfolio signals from cargo-cult formatting,
- build a better project case study,
- connect GitHub, Medium, and LinkedIn into one coherent hiring surface.

## Source base

The report draws on:

- DEV Community articles on GitHub hiring and portfolio design,
- résumé-screening coverage such as HR Dive,
- Reddit discussions from hiring managers and experienced developers,
- configuration best-practice references such as OneNine,
- and related material around demos, writing, and project presentation.

The full references are listed in the report itself:

- [`docs/github-profile-hiring-guide.en.md#references`](./docs/github-profile-hiring-guide.en.md#references)

## Repo structure

```text
github-rabbit-hole/
├── README.md
└── docs/
    └── github-profile-hiring-guide.en.md
```

## Suggested reading path

If you only want the practical part:

1. Open the [claim verification section](./docs/github-profile-hiring-guide.en.md#claim-verification)
2. Read the [step-by-step guide](./docs/github-profile-hiring-guide.en.md#step-by-step-guide)
3. Use the [final checklist](./docs/github-profile-hiring-guide.en.md#final-checklist)

If you want the nuance:

1. Read the [claim verification section](./docs/github-profile-hiring-guide.en.md#claim-verification)
2. Read [what was wrong or inaccurate](./docs/github-profile-hiring-guide.en.md#what-was-wrong-or-inaccurate)
3. Then apply the practical checklist
