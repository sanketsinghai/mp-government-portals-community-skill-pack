# Claude Usage

If this repository is opened directly in Claude Code or another Claude-based coding assistant, use `SKILL.md` as the canonical instruction file and `references/` as the source of truth for portal data.

## Disclaimer

This repository is **not an official Madhya Pradesh Government repository** and is **not maintained by the MP Government**. It is a community-maintained routing aid built around official public portal URLs.

## Working rules

- Always answer with official URLs when available.
- Do not invent or infer missing URLs.
- Route district queries to `references/districts.md`.
- Route service-platform queries such as Bhulekh, MPOnline, tenders, grievances, scholarships, and IGR to `references/egovernance.md`.
- Route electricity, water, and transport queries to `references/utilities.md`.
- Suggest related portals when it improves the answer.

## Reuse

For reusable personal installation, copy `.claude/skills/mp-government-portals/` into `~/.claude/skills/`.
