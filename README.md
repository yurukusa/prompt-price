# Prompt Price

**How much does this API call actually cost?**

Paste your prompt text and see the estimated cost across 30+ AI models instantly. No signup, no API key, no data sent anywhere.

## Try it

**[https://yurukusa.github.io/prompt-price/](https://yurukusa.github.io/prompt-price/)**

## Features

- Paste any text, see instant cost estimates across 28 models from 7 providers
- Output multiplier: adjust expected output length relative to input
- Template prompts for common use cases (code review, blog post, translation, etc.)
- Quality scores from Arena Elo, SWE-bench, and GPQA benchmarks
- Best value calculation (cost per quality point)
- 1K calls column for bulk cost estimation
- Zero dependencies, runs entirely in your browser

## How token estimation works

Since actual tokenizers vary by model, we use character-based estimation:
- English/Latin text: ~4 characters per token
- CJK characters: ~1.5 characters per token

This gives a reasonable approximation for cost comparison purposes.

## Related

- [LLM Price Calculator](https://yurukusa.github.io/llm-price/) — Monthly cost comparison
- [cc-toolkit](https://yurukusa.github.io/cc-toolkit/) — 106 free Claude Code analysis tools

## License

MIT
