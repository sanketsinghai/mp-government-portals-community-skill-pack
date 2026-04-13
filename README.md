# MP Government Portals Community Skill Pack

Community-maintained cross-agent knowledge pack for discovering official Madhya Pradesh government portals.

## Important Disclaimer

> This repository is **not an official Madhya Pradesh Government project** and is **not maintained by the MP Government**.
> It is a community-maintained routing and reference pack that links to official public portals.

## Why This Project Exists

People often know the service they need, but not the exact official portal.
This project organizes 269+ MP government portals into clear categories so citizens, developers, and researchers can quickly find the right official URL.

## Highlights

- 55 district collector portal references
- 45+ department portal references
- e-governance services: Bhulekh, MPOnline, tenders, scholarships, grievances
- utilities: electricity, water, transport
- cross-agent compatibility: Copilot, Claude, Claude Code, GPT-style assistants

## Quick Start

### Use it as a reference on GitHub

Start with:

- `references/egovernance.md`
- `references/districts.md`
- `references/departments.md`
- `references/utilities.md`

### Install for GitHub Copilot

```bash
mkdir -p ~/.copilot/skills
cp -R .github/skills/mp-government-portals ~/.copilot/skills/
```

### Install for Claude / Claude Code

```bash
mkdir -p ~/.claude/skills
cp -R .claude/skills/mp-government-portals ~/.claude/skills/
```

### Install for agents using `.agents/skills`

```bash
mkdir -p ~/.agents/skills
cp -R .agents/skills/mp-government-portals ~/.agents/skills/
```

### Use with GPT-style assistants

1. Create a custom GPT/project.
2. Paste `gpt/system-prompt.md` into system instructions.
3. Upload `SKILL.md` and all files from `references/`.
4. Validate with test prompts from `gpt/SETUP.md`.

## Example Prompts

- How do I check MP land records?
- Find the collector portal for Indore district.
- Where can I pay MP electricity bills?
- Which portal is used for MPPSC?
- Show official MP scholarship portals.

## Repository Structure

```text
.
├── SKILL.md
├── references/
├── .github/skills/mp-government-portals/
├── .claude/skills/mp-government-portals/
├── .agents/skills/mp-government-portals/
├── gpt/
├── CONTRIBUTING.md
├── MAINTENANCE.md
└── CLAUDE.md
```

## Scope

Included:

- Official MP portal references by category
- Multi-agent packaging for practical reuse
- Contributor and maintenance documentation

Not included:

- Automated scraping or uptime monitoring
- Legal/policy interpretation
- Unofficial or commercial portal directories

## Data Quality

URLs are curated from official public government websites. Since portals can move or change, verify important links before critical use and report broken links via issues or pull requests.

## Contributing

Contributions are welcome for broken links, missing portals, and categorization improvements.
See `CONTRIBUTING.md`.

## License

MIT License. See `LICENSE`.
