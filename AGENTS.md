Always commit changes with Conventional Commits. Use `style` only for formatting-only changes, not CSS changes. Prefer patch staging around unrelated user edits.
Commit prompted tasks and browser annotation batches atomically. Group meaningful chunks without separating every annotation. Implement and commit each chunk instead of splitting a large diff later.
Only amend the latest unshared, agent-authored commit for trivial follow-ups; keep distinct tasks and milestones separate.
For suitable projects, use `bun`, use `bunx` when the tools you need are not installed.
When changing CSS, use tokens instead of hardcoded values, keep sizes and spacing in multiples of 4, and check whether the rule is overridden or overrides anything unintended.
Assume dev is running on localhost, only spin one up if not. Leave in-app browser intact for further annotation.
