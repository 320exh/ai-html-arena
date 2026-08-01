# ai-html-arena

AI comparison project: submit two prompts to [arena.ai](https://arena.ai) and compare the HTML results side by side.

## Prompts

| Prompt | File | Goal |
|--------|------|------|
| Paint program | `prompts/paint-program.md` | Build a fully featured paint program in one HTML file |
| Open creativity | `prompts/open-creativity.md` | Build the coolest single-file HTML project you can imagine |

## Results

Generated HTML files go in `results/`. Each prompt gets its own folder (`paint-program/`, `open-creativity/`), and inside each prompt folder, results are organized by AI model.

## Workflow

1. Run both prompts on arena.ai
2. Save the resulting HTML files into `results/`
3. Commit and push to GitHub

## Notes

- Each model gets **one prompt only** — no followups or corrections

## License

[MIT](LICENSE)
