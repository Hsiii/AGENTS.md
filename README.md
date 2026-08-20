# AGENTS.md

My AGENTS.md, optimized for frontend development with GPT 5.5 in Codex.

## What it does

### Ensure Proper Commits
- Force agents to use correct [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) so commit history stays readable.
- Prevent agents from implementing everything at once THEN figure out how to split the huge changes into commits later, that takes incredibly long.
- Tell agents to amend or autosquash recent local follow-up work into the matching commit, while avoiding risky history rewrites across older or unrelated commits.
### Make Tooling Faster
- Prefer `bun` in suitable projects so agents do not default to slower `npm` commands in repos that already use Bun.
- Tell agents about `bunx`, so absent global packages do not block shell workflows.
### Enhance DX
- Prevent different agents from spinning up their own dev servers.
- Leave the in-app browser intact so an agent does not close it after one prompt and interrupt further annotation.
