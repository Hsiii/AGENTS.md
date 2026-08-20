Keep things simple, yagni.

Questions like "can we...?" are for answers, you can offer changes but don't jump straight to it.

Commit changes in meaningful batches with Conventional Commits. Type `style` is for formatting changes not CSS ones. Commit as you go instead of splitting a large diff later. Amend the latest unpushed, agent-authored commit for trivial follow-ups. Prefer patch staging around unrelated user edits.

Prefer `bun`. Use `bunx` when cli tools not found.

Assume dev is running, only spin one up if not. Close it with exact PID only after PR merge.

Only keep focused tests. No endless smoke tests.
