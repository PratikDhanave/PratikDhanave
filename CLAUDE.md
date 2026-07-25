# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is the **GitHub special profile repository** for the user `PratikDhanave` — the repo name matches the username, so GitHub renders `README.md` at the root as the banner on <https://github.com/PratikDhanave>. It contains no application code, no build system, and no tests. The only tracked file is `README.md`; editing it changes what every visitor sees on the profile page.

Note: this repo lives inside a larger multi-project workspace whose root `CLAUDE.md` (one directory up) describes ~100 unrelated projects. That parent guidance is about Go/Python builds and does **not** apply here — there is nothing to build in this repo.

## Working on the profile

- All work is editing Markdown in `README.md`. There is no lint/build/test step; "correctness" means the rendered GitHub Flavored Markdown looks right on the profile.
- Preview locally with any GFM renderer, or push to a branch and view it on GitHub. The `main` branch is what renders publicly.
- The README embeds external stat widgets (`github-readme-stats.vercel.app`, `github-readme-streak-stats.herokuapp.com`). These render server-side on the profile; broken image links usually mean the widget host is down or the `username=` query param was changed, not a repo problem.
- Keep the `Last updated: <Month Year>` line at the bottom current when making substantive edits.

## Content conventions to preserve

The README is a hand-maintained personal brand document — match its established voice and structure rather than restyling it:

- **Metrics are concrete and load-bearing** (e.g. "30K+ TPS", "57% cost reduction", "1M+ users"). Do not soften, round away, or invent them — every figure traces to a real engagement.
- **Featured projects are presented as Markdown tables** with `Project | What it does | Stack` columns, grouped by category (Multi-Agent AI / Backend & Distributed Systems). Follow that shape when adding a project.
- The tagline "Built with care, not with templates" reflects the intent — avoid generic filler, boilerplate section headers, or AI-template phrasing.
- Section emoji headers (`## 🎯`, `## 🚀`, etc.) are part of the visual identity; keep them consistent when adding sections.
