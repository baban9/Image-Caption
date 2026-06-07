# Image Captioning (Deep Learning)

Academic analysis of deep learning approaches to automatic image captioning. Documents model architectures, evaluation metrics, and literature review.

## Problem

Generate natural language descriptions of images using neural encoder-decoder architectures.

## Current state

This repository contains the written analysis (`Image Caption - Deep Learning Approach.pdf`). Runnable training and inference code is planned as a follow-up.

## Approach (documented)

- CNN encoder for visual features
- RNN/LSTM or attention-based decoder for caption generation
- BLEU and qualitative evaluation against reference captions

## Reproducibility

No executable pipeline yet. For related runnable work see:

- [Personal-Projects](https://github.com/baban9/Personal-Projects) (CV and NLP notebooks)
- [Machine-and-Influence-learning](https://github.com/baban9/Machine-and-Influence-learning)

## Tech stack (planned)

Python, PyTorch, COCO or Flickr8k dataset

## Next steps

1. Implement Show-and-Tell or attention-based captioning baseline
2. Add training script, evaluation metrics, and sample inference notebook
3. Pin dependencies and publish model checkpoints
