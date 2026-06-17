# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

This is **not a software project**. It is Nathan Hawk's professional knowledge base — a
Markdown-only career repository. There is no build, no tests, no dependencies. Work here is
reading, writing, and reorganizing prose.

**Primary purpose:** be the source of truth from which targeted outputs are generated —
tailored resumes for specific job listings, plus LinkedIn updates, recruiter summaries,
promotion packets, annual reviews, proposal bios, and interview prep. When given a job
description, pull the most relevant facts from the inventory and organization files and
assemble a targeted resume from `resumes/master.md`. Emphasize what the listing asks for;
**never invent experience.**

**This repo is public.** Anyone (including recruiters) can read it. Do not add sensitive
personal data — home address, phone number, government IDs, or salary figures. Assume every
word is world-readable and verifiable against public profiles.

Core narrative (`README.md`): *Technical leader who bridges software engineering, customer
communication, and business value.* The differentiator is not writing code — it is taking
ambiguous technical/business problems, working with customers, evaluating decisions through
ROI, and delivering practical software. Reinforce this in every output, guided by
`philosophy.md`.

## Source hierarchy (from README.md)

Every file has a tier. When facts conflict, the higher tier wins; outputs never become sources.

- **Gold** — raw truth: `organizations/*.md` (one file per employer/venture) and the raw facts
  in `inventory/experience.md` / `inventory/metrics.md`.
- **Silver** — synthesized summaries: the rest of `inventory/` (`accomplishments.md`,
  `professional-narrative.md`, `business-value-positioning.md`, `leadership.md`, `skills.md`,
  `brag-document.md`, `projects.md`, `future.md`).
- **Bronze** — application-specific outputs: `resumes/`, `opportunities/`, `promotion/`,
  `annual-reviews/`. These are generated *from* Gold/Silver and are never the source of truth.

## Layout

- **`organizations/`** — one file per role, the Gold unit of truth. Each follows a uniform
  template: *Title/Role · Dates · Core Themes · Responsibilities · Resume Bullets ·
  Positioning Note*. Files: `ara.md` (ARA — Staff SWE II, SPECTRE/FDA), `cities.md` (sole
  architect, retail SaaS), `okb3t.md` (CTO & Board Member), `stack-race.md` (founder),
  `like-a-boss.md`, `ritz-carlton-board.md`. Preserve this template when editing or adding.
- **`inventory/`** — `experience.md` is the chronological master career story (Gold);
  `metrics.md` collects hard numbers; the rest are thematic summaries (Silver).
- **`interviews/stories.md`** — STAR behavioral stories (Situation/Task/Action/Result),
  drawn from the organization files.
- **`resumes/master.md`** — the master resume; tailored resumes derive from it, not scratch.
- **`opportunities/<role>/`** — per-listing notes (e.g. `renewable-energy-senior-sde/`).
- **`promotion/`, `annual-reviews/`** — internal-advancement outputs.

## Conventions (from README.md — read before reorganizing)

- **Optimize for finding information, not eliminating duplication.** This repo *intentionally*
  duplicates facts (e.g. `inventory/experience.md` restates organization-file details) so key
  facts are easy to find. Do **not** "DRY out" the content — that is by design.
- **Never delete accomplishments from the inventory.** Add wins, praise, metrics, and
  leadership examples as soon as they happen; review quarterly.
- **Positioning Notes matter.** Several roles carry caveats — CTO/founder titles may read as
  outside-commitment distractions on conservative full-time applications; include or soften
  per the note in each file when tailoring.
- Many entries have an explicit *Need metric* / *Metrics To Find Later* placeholder. When real
  numbers surface, fill them into `inventory/metrics.md` and the relevant org file.
- Keep everything truthful — this backs real resumes and interviews and is publicly checkable.
