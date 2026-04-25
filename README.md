# magpie

Python framework for measuring hallucination in AI code review by verifying claims against source.

> **Status: pre-alpha (v0.0.1).** Under active development. API is unstable; do not rely on it yet.

> _Not affiliated with [magpie-align/magpie](https://github.com/magpie-align/magpie) (LLM alignment data synthesis), [Blinue/Magpie](https://github.com/Blinue/Magpie) (Windows upscaler), or any of several "Magpie" companies in adjacent industries._

## What it does

LLM code reviewers say things like *"function X has bug Y at line N."* Most claims are right. Some are confidently wrong (hallucinated). `magpie` measures how often a given AI reviewer hallucinates on a given codebase, by verifying each claim against actual source.

## Install

```bash
pip install magpie-eval
```

(The PyPI distribution is named `magpie-eval` while the bare `magpie` namespace is being reclaimed under [PEP 541](https://peps.python.org/pep-0541/). The Python import name is `magpie`.)

## License

MIT
