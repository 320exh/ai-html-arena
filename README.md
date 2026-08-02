# ai-html-arena-v1

A side-by-side comparison of how different AI models perform at generating single-file HTML projects. Two benchmark prompts are submitted to [arena.ai](https://arena.ai) for each model, and the resulting HTML files are compared:

| Prompt | File | What it tests |
|--------|------|---------------|
| Paint program | `prompts/paint-program.md` | **Execution accuracy** — can the model build a fully featured paint program in one HTML file on the first try? |
| Open creativity | `prompts/open-creativity.md` | **Creative capability** — how creative and impressive can the model be with a single-file HTML project? |

## Methodology

- Each model receives **one prompt per benchmark** — no follow-ups, corrections, or retries.
- Each model gets **one session/try** per prompt — if the result is broken, it stays broken. This preserves the honesty of a first-attempt comparison.
- The same prompt is used for every model within each benchmark, ensuring a fair comparison.

## Results

Generated HTML files live in `results/`, organized by prompt. Each prompt has its own output file per model.

## Repository notes

- `prompts/` is the source of truth — these are the exact prompts submitted to arena.ai.
- **Never edit HTML files in `results/`** — any manual modification, even a minor improvement, compromises the validity of the comparison. If a result is broken, regenerate it from the prompt.
- `CLAUDE.md` and `.gitignore` are not committed to the repo.

## License

[MIT](LICENSE)
