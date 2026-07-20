# AGENTS.md

My AGENTS.md, optimized for frontend development with GPT-5.6 in Codex.

## What it does

### Ensure Proper Commits
- Force agents to use correct [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) so commit history stays readable.
- Prevent agents from implementing everything at once THEN figure out how to split the huge changes into commits later, that takes incredibly long.
### Make Tooling Faster
- Prefer `bun` in suitable projects so agents do not default to slower `npm` commands in repos that already use Bun.
- Tell agents about `bunx`, so absent global packages do not block shell workflows.
### Unslop the CSS
- Force agents to use CSS tokens instead of splashing hard-coded values everywhere.
- Force CSS sizes and spacing in multiples of 4.
- Ask agents to check CSS cascade behavior because agents always miss it and break styles unintentionally.
### Enhance DX
- Prevent different agents from spinning up their own dev servers.
- Leave the in-app browser intact so an agent does not close it after one prompt and interrupt further annotation.
