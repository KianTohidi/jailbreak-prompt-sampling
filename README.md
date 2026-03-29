# Jailbreak Prompt Sampling

This repository contains the data sampling code used in our research. It reproducibly extracts jailbreak prompt samples from publicly available datasets on Hugging Face, for use in cybersecurity and AI safety analysis.

## Datasets

| # | Dataset | Label | Sample Size | Seed |
|---|---------|-------|-------------|------|
| 1 | [rogue-security/prompt-injections-benchmark](https://huggingface.co/datasets/rogue-security/prompt-injections-benchmark) | jailbreak | 100 | 42 |
| 2 | [allenai/wildjailbreak](https://huggingface.co/datasets/allenai/wildjailbreak)  | jailbreak | 100 | 42 |

## Requirements

- Python 3.8+
- Google Colab (recommended) or Jupyter Notebook
- A Hugging Face account with access to the listed datasets

## How to Run

1. Open the notebook in Google Colab
2. Add your Hugging Face token to Colab Secrets as `HF_TOKEN`
3. Run all cells in order

## Reproducibility

All samples are drawn with a fixed random seed (`seed=42`) to ensure results are identical across runs.

## License

This code is released under the MIT License. See `LICENSE` for details.
