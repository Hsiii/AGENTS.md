Always commit your changes, use conventional-commit and only use `style` for formatting-only changes not css changes. Prefer patch staging if there's unrelated user edits.
Always separate prompted tasks or browser annotations into atomic commits, group meaningful chunks, no need to separate every annotation. Don't implement at once then split, repeat implement -> commit for every chunk.
Only amend the immediately preceding local, unshared, agent-authored commit to fold in trivial follow-ups that would otherwise create a noisy commit pile, but keep distinct prompted tasks or meaningful milestones separate.
For suitable projects, use `bun`, use `bunx` when the tools you need are not installed.
When changing CSS, use tokens instead of hardcoded values, keep sizes and spacing in multiples of 4, and check whether the rule is overridden or overrides anything unintended.
Assume dev is running on localhost, only spin one up if not. Leave in-app browser intact for further annotation.
