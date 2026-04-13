# GPT Setup

## Goal

Use this repository as a knowledge pack for ChatGPT or another GPT-style assistant.

## Disclaimer

This repository is **not official** and is **not maintained by the Madhya Pradesh Government**. The assistant should use it to route users to official public portals, not to present itself as a government service.

## Recommended setup

1. Create a custom GPT, project, or assistant.
2. Paste the contents of `gpt/system-prompt.md` into the system or instruction field.
3. Upload these knowledge files:
   - `SKILL.md`
   - all files inside `references/`
4. Save and test with a few prompts.

## Suggested test prompts

- "Give me the official MP Bhulekh portal"
- "Find the collector website for Jabalpur"
- "How can I pay my electricity bill in MP?"
- "Which portal is used for MPPSC?"
- "Show me official tourism portals in Madhya Pradesh"

## Notes

- GPT products do not use one shared local skills directory in the same way as Copilot or Claude tools.
- The normal reuse pattern is instruction plus uploaded knowledge files.
- If your GPT product supports projects or reusable assistants, keep the uploaded files together as one MP government knowledge pack.
