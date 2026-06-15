# AGENTS.md

My AGENTS.md, optimized for frontend development with GPT 5.5 in Codex.

## Why

- Always commit changes so I can make small parallel changes across threads without worktrees.
- Force agents to use correct [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) so commit history stays readable.
- Avoid implementing everything at once and splitting later because patch staging takes much longer that way.
- Prefer `bun` in suitable projects so agents do not default to `npm` in repos that already use Bun, keeping tooling consistent.
- Prefer `bunx` for missing tools so absent global packages like `vercel` or `wrangler` do not block shell workflows.
- Use CSS tokens because that is the intended styling discipline for this repo.
- Keep CSS sizes and spacing in multiples of 4 because that is a common design principle.
- Check CSS override behavior because agents often miss it and break styles unintentionally.
- Assume a dev server is already running on localhost, and only start one if needed, so different agents do not spin up their own servers.
- Leave the in-app browser intact so an agent does not close it after one prompt and interrupt further annotation.
