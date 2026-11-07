# BoardGameArena

[Browse the public dataset](https://wenxiao7.github.io/boardgamearena-benchmark/)

This repository hosts the BoardGameArena public dataset website and its 900 questions. The dataset covers five games, three task types, and three reasoning types, with 20 questions in each of 45 subsets.

## Downloads

- [45 JSONL subsets and metadata mapping](data/boardgamearena-900.zip)
- [Combined JSONL file](data/boardgamearena-900.jsonl)
- [Question metadata mapping](data/metadata.json)

Each JSONL record contains `instruction`, `input`, and `output`. Question text is preserved from the source data, including literal `\n` sequences. The website displays these sequences as line breaks.

## Hosting

GitHub Pages serves the repository root on the `main` branch.
