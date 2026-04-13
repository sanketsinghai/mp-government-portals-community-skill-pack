<<<<<<< HEAD
# mp-government-portals-community-skill-pack
Community-maintained cross-agent knowledge pack for official Madhya Pradesh government portals, compatible with Copilot, Claude, Claude Code, and GPT-style assistants
=======
# MP Government Portals Skill Pack

A cross-agent knowledge pack for finding official Madhya Pradesh government portals.

This repository contains a curated directory of 269+ official MP government websites and service portals, packaged so it can be reused in GitHub Copilot, Claude, Claude Code, and GPT-style assistants.

## What is included

  - `.github/skills/mp-government-portals/`
  - `.claude/skills/mp-government-portals/`
  - `.agents/skills/mp-government-portals/`

## Primary use cases


## Repository structure

```text
.
├── SKILL.md
├── references/
├── .github/skills/mp-government-portals/
├── .claude/skills/mp-government-portals/
├── .agents/skills/mp-government-portals/
├── gpt/
├── CONTRIBUTING.md
└── MAINTENANCE.md
```

## How to use

### 1. Browse on GitHub

You can use this repository directly as a maintained reference directory of MP government portals.

Start with these files:

### 2. Install in GitHub Copilot / VS Code

Copy the prepared skill folder into your personal Copilot skills directory:

```bash
mkdir -p ~/.copilot/skills
cp -R .github/skills/mp-government-portals ~/.copilot/skills/
```

Project-local use is also possible:

```bash
mkdir -p your-project/.github/skills
cp -R .github/skills/mp-government-portals your-project/.github/skills/
```

After that, ask questions such as:

### 3. Install in Claude or Claude Code

Copy the Claude wrapper into your personal Claude skills directory:

```bash
mkdir -p ~/.claude/skills
cp -R .claude/skills/mp-government-portals ~/.claude/skills/
```

If you work with another agent runner that supports `.agents/skills`, use:

```bash
mkdir -p ~/.agents/skills
cp -R .agents/skills/mp-government-portals ~/.agents/skills/
```

If you open this repository directly in Claude Code, the root `CLAUDE.md` provides a lightweight entry point.

### 4. Use in GPT-style assistants

There is no single universal local skill folder for GPT products, so the normal pattern is:

1. Create a custom GPT, project, or assistant.
2. Paste the contents of `gpt/system-prompt.md` into the system instructions.
3. Upload the files from `references/` as knowledge files.
4. Optionally also upload `SKILL.md` for the topic map and response rules.

Detailed setup notes are in `gpt/SETUP.md`.

## Example prompts

Citizen-facing examples:

Developer and researcher examples:

## Scope

Included in v1:

Not included in v1:

## Data quality

This repository is curated from official public government websites. Portal locations can change over time. Verify important URLs before operational use and report outdated links through issues or pull requests.

## License

This repository is licensed under the MIT License. See `LICENSE`.

## Contributing

See `CONTRIBUTING.md` for portal update rules and contribution expectations.
>>>>>>> 75fcd7f (Initial cross-agent MP government portals skill pack)
