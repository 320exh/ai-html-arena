# ai-html-arena

AI comparison project: submit two prompts to [arena.ai](https://arena.ai) and compare the HTML results side by side.

## Prompts

| Prompt | File | Goal |
|--------|------|------|
| Paint program | `prompts/paint-program.md` | Build a fully featured paint program in one HTML file |
| Open creativity | `prompts/open-creativity.md` | Build the coolest HTML project it can imagine |

## Results

Generated HTML files go in `results/`. Each prompt gets its own output file.

## Workflow

1. Run both prompts on arena.ai
2. Save the resulting HTML files into `results/`
3. Commit and push to GitHub

## Notes

- `CLAUDE.md` and `.gitignore` are not committed to the repo
- `prompts/` is the source of truth for what was submitted
- `README.md` is auto-maintained — update it whenever prompts, results, or workflow steps change
