# NLP817:  Assignment 3

English to Afrikaans machine translation using fine-tuned MarianMT.

## Setup

```bash
pip install -r requirements.txt
```

## Run

Open `mt_assignment.ipynb` in Jupyter and run all cells top to bottom.

The notebook will:
1. Parse the provided `ee_mt.v0.1/` dataset
2. Use the downloaded OPUS af-en augmentation data
3. Fine-tune `Helsinki-NLP/opus-mt-en-af` in two phases
4. Compute BLEU scores (baseline and fine-tuned)
5. Show qualitative translation examples

Outputs are saved to `results/`.

## Data

Provided dataset: `ee_mt.v0.1/` 
External data: Helsinki-NLP/opus-100 af-en subset

## Hardware

Tested on CPU. Training takes ~1-3 hours.
