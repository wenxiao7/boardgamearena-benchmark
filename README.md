# BoardGameArena

[Explore the test-mini dataset](https://wenxiao7.github.io/boardgamearena-benchmark/)

This repository hosts the BoardGameArena test-mini dataset website. The dataset covers five games, three task types, and three reasoning types across 45 subsets. The website previews one example from each subset.

## Downloads

- [test-mini dataset: JSONL subsets and metadata mapping](data/test-mini-dataset.zip)
- [Combined JSONL file](data/test-mini-dataset.jsonl)
- [Question metadata mapping](data/metadata.json)

Each JSONL record contains `instruction`, `input`, and `output`. Question text is preserved from the source data, including literal `\\n` sequences. The website displays these sequences as line breaks.

## Hosting

GitHub Pages serves the repository root on the `main` branch.
