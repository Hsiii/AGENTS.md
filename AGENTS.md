## Edit & Commit
- Commit your changes in atomic conventional-commit chunks, prefer patch staging to exclude unrelated edits, and use `style` only for formatting-only changes

## Frontend
- Use `bun` when applicable
- Reuse existing components unless a new one is necessary
- Apply outlines only on `:focus-visible` not on `:focused`
- Always tokenize colors, fonts, and spacing
- Use dimensions and spacing in multiples of 4 where practical
- When changing CSS, check whether the rule is overridden and whether it overrides anything unintended

## Browser & Chrome
- Use Chrome for browser tasks unless explicitly told otherwise
