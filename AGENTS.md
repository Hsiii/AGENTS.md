## Edit & Commit
- Always commit your changes, do it in atomic chunks w/ conventional commits
- Never misuse `style` type, it's for format changes
- Stage only hunks you changed, never commit unrelated edits
- There always might be other agents editing
- Run git commands serially to prevent stale git lock

## Frontend
- Use `bun` when applicable
- Reuse existing components unless a new one is necessary
- Apply outlines only on `:focus-visible` not on `:focused`
- Always tokenize colors, fonts, and spacing
- Use dimensions and spacing in multiples of 4 where practical
- When fixing css, check all cascade for collision

## Browser & Chrome
- For Browser Use, use Chrome
