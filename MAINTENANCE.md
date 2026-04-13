# Maintenance

## Maintenance model

This repository is maintained as a curated knowledge pack, not as an automated crawler.

## Canonical source files

- `SKILL.md` is the canonical instruction source.
- `references/` is the canonical portal dataset.
- Platform wrappers in `.github/skills/`, `.claude/skills/`, and `.agents/skills/` should mirror the root files.

## Update workflow

1. Update `SKILL.md` if routing, scope, or response rules change.
2. Update the relevant file in `references/`.
3. Sync the same changes into the platform-specific skill folders.
4. Update `README.md` if the installation flow or scope changed.

## Validation rules

- Verify that each URL is official before adding or changing it.
- Prefer HTTPS versions of official portals where available.
- For district portals, retain both NIC and MP government URLs when available.
- For electricity services, preserve zone-specific guidance.
- Keep the wording descriptive but neutral.

## Suggested review cadence

- Light review: monthly for major citizen-service portals
- Full review: quarterly across all categories
- Immediate review: when a user reports a broken link or domain change

## Out-of-scope work

The following are intentionally out of scope for v1:
- Automated link scraping
- Continuous uptime monitoring
- Exhaustive API extraction
- Support for unofficial mirrors or aggregator websites

## Release guidance

A good release should confirm:
- Root and platform wrapper files are consistent
- The skill folder name matches `mp-government-portals`
- Example prompts still map to the documented reference files
- Installation instructions in `README.md` still match the repository layout
